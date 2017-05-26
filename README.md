# Project-of-bus
Tentaremos criar um projeto para nos ajudar em um terminal de ônibus nos auxiliando como qual baú saíra de acordo com a quantidade de funcionários disponíveis.


#include<stdio.h>

int usuarios, motoristas;

int main(){
    
     printf("\tControle de Saida De Onibus\n"); //Exibe o titulo do Codigo
     printf("\t\t\t Por: Douglas e Gabriel!\n\n\n");  //Exibe os criadores do Codigo na tela 


    
    //Quantidade De Usuarios
    printf("Quantidade de usuarios: ");
    do{
       scanf("%d",&usuarios);
    }
    while(usuarios < 0); 
    
    //Quantidade De Motoristas
    printf("Quantidade de motoristas: ");
    do{
       scanf("%d",&motoristas);
    }
    while(motoristas < 0); 
    
    //Condições
    if(motoristas > 0) {
      if(motoristas < 2 || usuarios < 15 ) printf("\n Sai minibus");
      if (motoristas >= 2 && usuarios >=15) printf("\n Sai bus");
    }
    else printf("\n Nao sai Bus nem Minibus");
                                                
    getch();
       
}
