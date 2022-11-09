## Program 10: Write a program to show the work of goto statement
```C
#include<stdio.h>
int main()
{
int i=1;
START: //label for goto statement
    printf("\n%d",i);
    i++;
    if(i<=5)
    goto START;
}
```
##Output:
```
1
2
3
4
5
```
