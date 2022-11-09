## Program9: write a program to show the work of switch case statement
```C
#include<stdio.h>
void main()
{
int day;
printf("enter day number :");
scanf("%d",&day);
switch(day)
{
case 1: printf("monday");break;
case 2: printf("tuesday");break;
case 3: printf("wednesday");break;
case 4: printf("thursday");break;
case 5: printf("friday");break;
case 6: printf("saturday");break;
case 7: printf("sunday");break;
default: printf("wrong input");
}
}
```
### Output:
```
enter a day number:5 
friday
```
