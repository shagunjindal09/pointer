# void pointer
#include <stdio.h>

int main()
{
   int a=10;
   
   int *p;
   
   p=&a;
   
   printf("the address of %d\n and valure of %d\n ",p,*p);
    
    void *p0;
    
    p0=p;
    
    printf("the address is %d",p0);
   

    return 0;
}
