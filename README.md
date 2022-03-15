# QUEST-O-01-LOGICA-2
#include <stdlib.h> 
int num(int z){
int i, soma=0;
for(i=2; i<z; i++){
soma=soma+i;
}
return soma;
}
int main()
{
int n,x=0;
printf("Digite um numero inteiro positivo: ");
scanf("%d", &n);
x= num(n);
printf("\n A soma dos valores entre 1 e %d é: %d \n\n", n, x);
return 0;
}
