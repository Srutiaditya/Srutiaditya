#include<stdio.h>
int main()
{
    int a,sum=0;
    printf("Enter the value");
    scanf("%d",&a);
        for(int i=1;i<a;i++)
        {
           if(a%i==0)
           
               sum=sum+i;
           
        }
        if(sum>a)
        {
            printf("Abandant Number");
        }
        else
        {
            printf("Deficent number");
        }
        return 0;
}

