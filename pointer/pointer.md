# pointer1
#include <stdio.h>

int main()
{
   int a=1034;
   
   int *p;
   
   p= &a;
   
   printf("%d\n",p);
   
   printf("%d\n",*p);
   
   printf("the size of int of %d\n ",sizeof(int));
   
   printf("the address of %d and the value of %d",p+1,*(p+1));
   
   char *p0;
   
   p0= (char*)p;
   
   printf("size of char is %d\n",sizeof(char));
   
   printf("the address of %d\n and the value of %d\n ",p0,*p0);
   
   printf("the address of %d and the value of %d", p0+1,*(p0+1));

    return 0;
}
