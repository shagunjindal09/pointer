# pointer to pinter
#include <stdio.h>

int main()
{
   int a=10;
   
   int *p=&a;
   
   *p=15;
   
int **q=&p;

int ***r=&q;

printf("%d\n",*p);

printf("%d\n",*q);

printf("%d\n",**q);

printf("%d\n",**r);

printf("%d\n",***r);

***r=45;

printf("%d\n",a);

**q=*p+2;

printf("%d",a);

    return 0;
}
