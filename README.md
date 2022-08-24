#include<stdio.h>
#include<conio.h>
int main()
{
int n, i, j;
printf("Enter the number of rows: ");
scanf("%d",&n);
for(i = n; i >= 1; i--)
{
for(j = 1; j <= i; j++)
{
printf("%d",j);
}
printf("\n");
}
return 0;
}

Output:
enter n value:6
6
65
654
6543
65432
654321
