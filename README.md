#include <stdio.h>
void main()
{
  int a,b;
  printf("Enter the two numbers a and b");
  scanf("%d %d",&a,&b);
  printf("\nThe numbers before swapping:\n a=%d \n b=%d",a,b);
  a=a+b;
  b=a-b;
  a=a-b;
  printf("\n the numbers after swapping:\n a=%d \n b=%d",a,b);
 }
