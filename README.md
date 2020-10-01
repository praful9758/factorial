# factorial
#include<stdio.h>
main()
{
int i,n,fact=1;
printf("kiska factorial chahiye?");
scanf("%d",&n);
for(i=n;i>=1;i--)
{
    fact*=i;
}
printf("factorial of %d is %d",n,fact);
}
