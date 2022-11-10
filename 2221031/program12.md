## Program 13: Write a program to show the work of break statement
```C
#include <stdio.h>

int main()
{
 int i;

 for(i=10;i>0; i--)
 {
  if(i==6)
   {
     printf("\n Coming out from for Where i = %d\n", i);
     break;
   }
  printf(" %d  ",i);
 }

}
```
## OUTPUT:
10   9   8   7  
 Coming out from for Where i = 6
