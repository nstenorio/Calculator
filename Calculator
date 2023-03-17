Calculadora em C

#include <stdio.h>

int main()
{
    float x;
    float y;
    float result;
    int op;
    
    printf("\nSeja bem-vindo a Calc Mjölnir... \n");

COND:

    printf("\nDigite o primeiro valor:\t\n");
         scanf("%f", &x);
    printf("\nDigite 1 para Soma, 2 para Subtração, 3 para Multplicação e 4 para Divisão\t\n");
         scanf("%i", &op);
         if(op > 4)
            printf("\nOpção Inválida, Selecione uma Operação para continuar: \t\n");
                scanf("%i", &op);
    printf("\nCerto, Agora digite o segundo valor: \t\n");
         scanf("%f", &y);
    
    if(op == 1){
        printf("\nO resultado é: %f", x+y);
    }
    if(op == 2){
        printf("\nO resultado é: %f", x-y);
    }
     if(op == 3){
        printf("\nO resultado é: %f", x*y);
    }
     if(op == 4){
        printf("\nO resultado é: %f", x/y);
    }
  
    
    printf("\nDeseja realizar uma nova Operação? 1(Sim) 2(Não)\t\n");
        scanf("%i", &op);
    if(op == 1){
        goto COND;
    }    
    else 
        printf("\nAté Breve...\t\n");
    
    
    return 0;
}
