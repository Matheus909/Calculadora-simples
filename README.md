#include <stdio.h>

int main() {

    int op;
    float n1, n2;

    printf("Digite o primeiro numero: ");
    scanf("%f", &n1);

    printf("Digite o segundo numero: ");
    scanf("%f", &n2);

    printf("\nEscolha a operacao:\n");
    printf("1 - Soma\n");
    printf("2 - Subtracao\n");
    printf("3 - Multiplicacao\n");
    scanf("%d", &op);

    if(op == 1) {
        printf("Resultado = %.2f\n", n1 + n2);
    }
    else if(op == 2) {
        printf("Resultado = %.2f\n", n1 - n2);
    }
    else if(op == 3) {
        printf("Resultado = %.2f\n", n1 * n2);
    }
    else {
        printf("Opcao invalida\n");
    }

    return 0;
}
