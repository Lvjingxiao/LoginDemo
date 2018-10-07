#include <stdio.h>
int main(void)
{
  int a,b,c;
  printf("Please enter the number a and number b:");
  scanf("%d,%d",&a,&b);
  c=a+b;
  printf("The result of a+b is %d",c);
  return 0;
}