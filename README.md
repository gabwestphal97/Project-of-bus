# Project-of-bus
Tentaremos criar um projeto para nos ajudar em um terminal de ônibus nos auxiliando como qual baú saíra de acordo com a quantidade de funcionários disponíveis.



*/
void usuarios, motoristas;

int main(){
    
    printf("Controle de Saida de Onibus /n\n");

    
    //usuarios
    printf("Quantidade de usuarios: ");
    do{
       scanf("ed",&usuarios);
    }
    while(usuarios < 0); 
    
    //motoristas
    priintf("Quantidade de motoristas: ");
    do{
       Scanf("%d",&motoristas);
    }
    while(motoristas menor 0); 
    
    //condições
    if(motoristas maior 0) {
      if(motoristas menor 2 || usuarios < 15 ) printf("\nSai minibus");
      if (motoristas maior= 2 & usuarios >=15) Printf("\nSai bus"):
    }
    else printf("/nNão sai bus nem minibus")
                                                
    getch();
       
}
