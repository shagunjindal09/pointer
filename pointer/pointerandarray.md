# pointer and array
#include <stdio.h>

int main()
{
    int a[]={2,3,4,5,6};
    
    int i;
    
    for(i=0;i<5;i++){
    
        printf("addres of %d\n",&a[i]);
        
        printf("address of %d\n",a+i);
        
        printf("value of %d\n",a[i]);
        
        printf("value of %d\n",*(a+i));
    }

    return 0;
}
