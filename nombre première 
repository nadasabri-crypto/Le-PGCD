#include <stdio.h>

int main() {
    int a, b;
    scanf("%d %d", &a, &b);

    int x = a, y = b;

    printf("Mahaal Al-PGCD:\n");

    while (y != 0) {
        int r = x % y;
        printf("%d = %d * (%d) + %d\n", x, y, x / y, r);
        x = y;
        y = r;
    }

    printf("PGCD(%d, %d) = %d\n", a, b, x);
    return 0;
}