#include <stdio.h>
    int prime_number(int number)
    {
        int multiplier;
        for (int multiplier = 2; multiplier <= number/2 ; multiplier++)
        {
            if(number % multiplier == 0)
            {
                return 0;
            }
        }
        return 1;
    }

    int main()
    {
        for (int i = 500; i <= 600 ; i++)
        {
           if (prime_number(i) == 1)
           {
               printf("%d \n",i);
           }
        }
        return 0;
    }


