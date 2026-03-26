# M4-D4
AIM:

Write a C program to count the total number of words in a given string using function.

PROGRAM:
```
#include <stdio.h>
int main()
{
    char a[100];
    fgets(a,100,stdin);
    int i,count=1;
    for(i=0;a[i]!=0;i++)
    {
        if(a[i]==' ')
        {
            count++;
        }
    }
    printf("%d",count);
}
```
PROGRAM:
<img width="755" height="334" alt="image" src="https://github.com/user-attachments/assets/6cd81cbc-b9d9-4a01-8961-6d0a55f417f1" />
RESULT:
Thus the code run successfully!
