#include <stdio.h>

int main() {
    int a, b, r;

    printf("Entrez le 1er et le 2ème nombre : ");
    scanf("%d %d", &a, &b);

    while (b != 0) {
        r = a % b;
        a = b;
        b = r;
    }

    printf("\nLe PGCD est : %d\n", a);
    return 0;
}