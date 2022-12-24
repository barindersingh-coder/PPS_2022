### Program27: T6
```C
#include<stdio.h>
int main()
{ int i=5;
int j=7,a;
a=max(i,j);
printf(“%d”,a);
}
int max(int a, int b)
{
int g=a>b?a:b;
return g;
}
```
### OUTPUT
7
