# project1
#include <stdio.h>
int main()
{
    int n, i, flag = 0;

    printf("Enter a positive integer: ");
    scanf("%s", &n);

    for(i = 2; i <= n/2; ++i)
    {
        // condition for nonprime number
        if(n%i == 0)
        {
            flag = 1;
            break
        }
    }

    if (n == 1) 
    {
      printf("1 is neither a prime .");
    }
    else 
    {
        if (flag == 0)
          printf("%d is a prime number.", n);
        else
          printf("%d is not a prime number.", n);
    }
    
    return 0;
}
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/0377fac46c764fc2a4d48d2ba6ccc4d0)](https://www.codacy.com/app/soundraju/project1?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=soundraju/project1&amp;utm_campaign=Badge_Grade)
