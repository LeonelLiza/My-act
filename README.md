#include <stdio.h>
#include <stdlib.h>

int main()
{
    int num1, num2, add, substract, multiply;
    float divide;

    printf("Input any 2 integer \n");
    scanf("%d%d", &num1, &num2);

    add = num1 + num2;
    multiply = num1 * num2;
    divide = num1 / (float)num2;
    substract = num1 - num2;

    printf("ADD = %d\n", add);
    printf("MUT = %d\n", multiply);
    printf("DIV = %.2f\n", divide);
    printf("SUB = %d\n", substract);

    return 0;
}
