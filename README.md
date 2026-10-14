
#include <stdio.h>

int main()
{
    float a, b, sum, average;

    printf("Enter two numbers: ");
    scanf("%f %f", &a, &b);

    sum = a + b;
    average = sum / 2;

    printf("Sum = %.2f\n", sum);
    printf("Average = %.2f\n", average);

    return 0;
}
# addition_average.c