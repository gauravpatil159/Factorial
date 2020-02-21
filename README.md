# Factorial
find factorial
#include<stdio.h>
void main()
{
    auto int n,i;
    
    
    printf("Enter value=");
    scanf("%d",&n);
    for(i=n;i>1;i--)
    {
    n=n*(i-1);
    
    }

    printf("Factorial = %d",n);/*prob to get factorial of higher no see data types in details*/

}
