# cce20211
##找零錢

#include <stdio.h>
int main ()
{
	int n;
	scanf("%d",&n);
	int a =n/50;
	int b = n%50/5;
	int c =n%5;
	
	printf("%d=50*",n);
	printf("%d+5*%d+1*%d\n",a,b,c);
	}
  
