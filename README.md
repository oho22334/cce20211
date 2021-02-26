# cce20211
## 找零錢

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
  

## 因數個數

#include <stdio.h>
int main ()
{
	int n,sum=0;
	scanf("%d",&n);
	for(int i=1;i<=n;i++){
		if(n%i==0)
		sum++;
		}
		printf("%d\n",sum);
		
}
## 找倍數

#include <stdio.h>
int  main()
{
	int a[10],ans=0;
	
	for(int i=0;i<10;i++){
		scanf("%d",&a[i]);
		if(a[i]%3==0)
		ans++;
		}
		printf("%d\n",ans);
}
## 整數轉換為等級

#include <stdio.h>
int main ()
{
	int n;
	scanf("%d",&n);
	if(n>=90)
	printf("A\n");
	else if (n<90&&n>=80)
	printf("B\n");
	else if (n<80&&n>=60)
	printf("C\n");
	else printf("F\n");
}
## 分式化簡

#include <stdio.h>
int main ()
{
 int a,b,c=0;
 scanf("%d%d",&a,&b);
 for(int i=1;i<a;i++){
 	if(a%i==0&&b%i==0)
 	c=i;
}
printf("%d %d\n",a/c,b/c);
}
