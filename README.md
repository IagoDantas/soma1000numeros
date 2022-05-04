# soma1000numeros
Calcular e exibir a soma dos 1000 primeiros números inteiros, feito em C


/***SOMA***/

#include <stdio.h>


int main(){
    int soma, i;
    soma = 0;
    for(i=1; i<=1000;i++)
    {
        soma = soma + i;
    }
    printf("%d", soma);
}
*
