# Exercicio3

#include <stdio.h>
#include <stdlib.h>

int main()
{
    system("color 0b");
    int i;

    for (i=1; i<=200; i++)
    {
        if (i % 2 == 0)
        {
            printf("Numeros pares %d\n",i);
        }
    }

    return 0;
}
