# array as function argument
#include <stdio.h>

int sum_of_number(int a[],int size)
{
    int i,sum=0;
    
    for(i=0;i<size;i++){
    
        sum+=a[i];
    }
    return sum;
}

int main()
{
    int a[]={2,3,4,5,5};
    
    int size= sizeof(a)/sizeof(a[0]);
    
    int total=sum_of_number(a,size);
    
    printf("sum of elements %d\n",total);

   
}
