#include<stdio.h>
int main()
{
	int l,b;
	int a,p;
	printf("\n Length & Breadth:  ",l,b);
	scanf("%d%d",&l,&b);
	a=l*b;
	p=2*l+2*b;
	printf("\n Area:%d",a);
	printf("\n Perimeter:%d",p);
	if(a>p)
	{
		printf("\n The area is greater than perimeter");
	}
	else
	printf("\n The area is not greater than perimeter");
	
}
