# CSA0375-DATASTRUCTURES
1. PROGRAM FOR MATRIX MULTIPLICATION 
#include<stdio.h>
int main()
{
	int a[2][2],b[2][2],c[2][2];
	int i,j,k,sum;
	printf("Enter A Matrix\n");
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
	  {
	   scanf("%d",&a[i][j]);
      } 
	}
	
	printf("Enter B Matrix\n");
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
	  {
	   scanf("%d",&b[i][j]);
}
}
	for(i=0;i<2;i++)
	{
	  for(j=0;j<2;j++)
    {
	   c[i][j]= 0;
	   for(k=0;k<2;k++)
	{
		c[i][j]+= a[i][k]*b[k][j];
		
	}
    } 
   }
   
   printf("\nthe multiplication of two matrices \n");
   	for(i=0;i<2;i++)
   	{
	   
   	 for(j=0;j<2;j++)
   {
   	
   	printf("%d  ",c[i][j]);
	   	   }   	
	   	   printf("\n");
	   }
}
<img width="960" alt="2022-09-20" src="https://user-images.githubusercontent.com/112490847/191183074-1b0292bf-14b8-4a2a-b170-b41d67b54edb.png">


PROGRAM 2:ODD OR EVEN NUMBERS

#include <stdio.h>
int main()
{
    int num1, rem1;
 
    printf("Input an integer : ");
    scanf("%d", &num1);
    rem1 = num1 % 2;
    if (rem1 == 0)
        printf("%d is an even integer\n", num1);
    else
        printf("%d is an odd integer\n", num1);
}

<img width="960" alt="2022-09-20 (2)" src="https://user-images.githubusercontent.com/112490847/191201481-bf18cfc2-6337-459a-8845-3aeddff3447e.png">

PROGRAM 3:
