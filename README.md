#include<stdio.h>
int main()
{
    int num=1234,rem,originalnum,reversed=0;
    originalnum=num;
    while (num!=0)
    {
        rem=originalnum%10;
        reversed=reversed*10+rem;
        num/=10;
    }
    if (originalnum==num)
    { 
        printf("%d is an palindrome number\n",originalnum);
    }
    else 
    {
        printf("%d is an not palindrome number\n",originalnum);
    }
    return 0;
}
