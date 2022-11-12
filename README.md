//# sum-of-1-10number.c//
#include<stdio.h>
int main()
{
    int i=1,sum;
    while(i<=10)
    {
        sum+=i;
        i++;
        printf("\nsum=%d",sum);
    }
    return 0;
}
