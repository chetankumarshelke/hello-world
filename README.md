// addition of two matrix

#include<stdio.h>
main()
{
	int a[10][10], i,j,b[10][10],n;
	printf("enter the size of matrix");
	scanf("%d", &n);
	printf("\n enter the matrizx elements\n");
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			scanf("%d",&a[i][j]);
		}
	}

	printf("\n enter the matrizx elements\n");
	for(i=0;i<n;i++)
	{
		for(j=0;j<n;j++)
		{
			scanf("%d", &b[i][j]);
		}
	}
		printf("sum of two matrix is : \n");
		for(i=0;i<n;i++)
		{
			for(j=0;j<n;j++)
		{
		
		printf("%d  ", a[i][j]+b[i][j]);
		}
		printf("\n");
	}
	}

