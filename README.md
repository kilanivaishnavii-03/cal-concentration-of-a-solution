# cal-concentration-of-a-solution
using for loop
#incude<stdio.h>
int main()
{
int n, i;
float m,v,c;
printf("enter the number of samples");
scanf("%d",&n);
for(i=1;i<=n;i++)
{
printf("\n sampe %d:\n",i);
printf("enter mass (m):");
scanf("%f",&m);
printf("enter voume (v):");
scanf("%f",&v);
if(v !=0)
{
c=m/v;
printf("volume cannot be zero!/n");
}
}
return 0;
}
