# If..else
Greatest between 3 no.s
#include<stdio.h>
#include<conio.h>
void main()
{
int a,b,c;
clrscr();
printf("Enter the 3 no.s:");
scanf("%d%d%d",&a,&b,&c);
if(a>b && b>c)
{
printf("%d is greatest",a);
}
else if(a<b && b>c)
{
printf("%d is greatest",b);
}
else
{
printf("%d is greatest",c);
}
getch();
}
