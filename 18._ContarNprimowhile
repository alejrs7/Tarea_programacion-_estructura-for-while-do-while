#include <stdio.h>

int esPrimo(int num) {
    if (num <= 1) return 0;
    for (int i = 2; i <= num / 2; i++) {
        if (num % i == 0) return 0;
    }
    return 1;
}

int main() {
    int n, count = 0;
    int i = 2;  // Inicializamos i en 2 porque el 1 no es primo

    printf("Introduce un número: ");
    scanf("%d", &n);

    // Usamos while en lugar de for para contar los números primos
    while (i <= n) {
        if (esPrimo(i)) count++;
        i++;
    }

    printf("Hay %d números primos hasta %d\n", count, n);
    return 0;
}
