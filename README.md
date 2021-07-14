# nepalnationalflag
Here is the code in C programming language to print pattern of Nepal national Flag using nested for-loop.





#include <stdio.h>

int main()
{
    int i, j;
    for (i = 1; i <= 13; i++)
    {
        for (j = 1; j <= i; j++)
        {
            if (j == 1 || i == 13 || i == 2 || (j == i) || (j == 2 && (i == 8 || i == 9)) || (i == 10 && (j == 6 || j == 3)) || (i == 11 && (j == 4 || j == 5)) || (j == 7 && (i == 9 || i == 8)) || (i == 9 && (j == 4 || j == 5)))
            {

                printf("* ");
            }
            else
            {
                printf("  ");
            }
        }
        printf("\n");
    }
    for (i = 2; i <= 15; i++)
    {
        for (j = 1; j <= i; j++)
        {
            if (j == 1 || i == 15 || i == 1 || (j == i) || ((j == 4 || j == 5) && (i == 7 || i == 12)) || ((i == 8 || i == 9 || i == 10) && (j == 3 || j == 6)) || ((i == 11 && (j == 3 || j == 6))))
            {
                printf("* ");
            }
            else
            {
                printf("  ");
            }
        }
        printf("\n");
    }
    printf("\n Nepal National Flag Pattern By LEKHNATH POKHREL.");
    return 0;
}


