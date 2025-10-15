#include <stdio.h>
#define PI 3.1417

int main()
{
    float area, diametro;
    printf("Diametro: ");
    scanf_s("%f", &diametro);

    diametro = diametro / 2;
    area = PI * diametro * diametro;

    printf("Area del circulo: %.2f", area);
}
