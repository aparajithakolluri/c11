#include <stdio.h>
int max(int a, int b){
    return (a>b)? a:b;
}
int main()
{
   int x,y;
   printf("enter the value of x:");
   scanf("%d",&x);
    printf("enter the value of y:");
   scanf("%d",&y);
   printf("maximum: %d\n",max(x,y));
    return 0;
}
