// Online C compiler to run C program online
#include<stdio.h>
int main()
{
    int a=10,b=20,c=30;
    printf("%d==%d\n",a,b,c,a==b);
    printf("%d==%d\n",a,b,c,a==c);
    printf("%d>%d\n",a,b,c,a>b);
    printf("%d>%d\n",a,b,c,a>c);
    printf("%d<%d\n",a,b,c,a<b);
    printf("%d<%d\n",a,b,c,a<c);
    printf("%d!=%d\n",a,b,c,a!=b);
    printf("%d!=%d\n",a,b,c,a!=c);
    printf("%d<=%d\n",a,b,c,a<=b);
    printf("%d<=%d\n",a,b,c,a<=c);
    printf("%d>=%d\n",a,b,c,a>=b);
    printf("%d>=%d\n",a,b,c,a>=c);
    
    return 0;
}
