#include <stdio.h>

int main() {
    float num1, num2, num3;

    // Solicita os três valores ao usuário
    printf("Digite o primeiro valor: ");
    scanf("%f", &num1);

    printf("Digite o segundo valor: ");
    scanf("%f", &num2);

    printf("Digite o terceiro valor: ");
    scanf("%f", &num3);

    // Verifica qual é o menor valor
    float menor = num1;
    if (num2 < menor) {
        menor = num2;
    }
    if (num3 < menor) {
        menor = num3;
    }

    // Exibe o menor valor
    printf("O menor valor é: %.2f\n", menor);

    return 0;
