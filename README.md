#include<stdio.h>

int main(){
    //Dados da primeira carta
    char nome1[50]="País A";
    float populacao1=1000000;
    float area1=50000;
    float pib1=500000000;

    //Dados segunda carta 
    char nome2[50]="País B";
    float populacao2=2000000;
    float area2=100000;
    float pib2=1000000000;

    //Cálculo dos atributos 
    float densidade1=populacao/area1;
    float pib_per_capita1=pib1/populacao1;

    float densidade2=polacao2=area2;
    float pib_per_capita2=pib2/populacao2;
     
     //Exibição dos resultados
     printf("Carta 1:\n");
     printf("Nome:%s\n",nome1);
     printf("Polação:%.0f\n",polucao1);
     printf("Área:%.0f\n",area1);
     printf("PIB:%.0f\n",pib1);
     printf("Densidade Polulacional:%.2f\n",densidade1);
     printf("PIB per Capita:%.2f\n",pib_per_capita1);

     printf("\nCarta2:\n");
     printf("Nome:%s\n",nome2);
     printf("População:%.0f\n",polulacao2);
     printf("Área:%.0f\n",area2);
     Printf("PIB:%.0f\n",pib2);
     Printf("Densidade Populacional:%.2f\n",densidade2);
     printf("PIB per Capita:%.2f\n",pib_per_capita2);

     return 0;
     
}