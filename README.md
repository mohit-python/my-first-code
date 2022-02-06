# my-first-code
//printing prime numbers upto number
#include<stdio.h>
#include<math.h>
void main()
{
int i,j,n,logic;
printf("enter your number");
scanf("%d",&n);
printf("prime numbers are : \n");
for(i=0;i<=n;i++)
{
  logic=0;
  for(j=1;j<=n;j++)
  {
    if(i%j==0)
    logic++;
   }
  if(logic==2)
  printf("%d",i);
}
getch();
}
