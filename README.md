#include<stdio.h>
int main()
{
    int a;
    printf("Enter the side of the square : ");
    scanf("%d",&a);
    printf("The area of sqaure is %d",as(a));
}
int as(int a)
{
    a=a*a;
    return a;
}

#include<stdio.h>
int main()
{
    int n;
    printf("Enter the number : ");
    scanf("%d",&n);
    printf("The given number is %d\n",n);
    inc(n);
    printf("After increement is %d\n",n);
}
void inc(int n)
{
    n=n+1;
    printf("Increement = %d\n",n);
}


#include<stdio.h>
int main()
{
    int n;
    printf("Enter the number : ");
    scanf("%d",&n);
    printf("The given number is %d\n",n);
    inc(&n);
    printf("After increement is %d\n",n);
}
void inc(int *n)
{
    *n=*n+1;
    printf("Increement = %d\n",*n);
}
