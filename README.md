# AtividadeComC2

#include <stdio.h>
#include <stdlib.h>

int main() { 

float nota1;
float nota2;
float nota3;
float nota4;

// Cálculo de media de 4 notas
    printf("Digite a primeira nota: ");
	scanf("%f", &nota1);
	printf("Digite a segunda nota: ");
	scanf("%f", &nota2);
	printf("Dite a terceira nota: ");
	scanf("%f", &nota3);
	printf("Digite a quarta nota: ");
	scanf("%f", &nota4);
	
	float media = nota1+nota2+nota3+nota4 /4;
	printf("Nota da media: %f", media);
	
return 0;
}
