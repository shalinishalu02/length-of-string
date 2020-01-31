#include<stdio.h>
void main ()
{
    char str[20];
    int count=0,i;
    printf("enter the string");
    scanf("%s",&str);
    for(i=0;str[i]!='\0';i++)
    {
        count++;
    }    
    printf("length=%d",count);
    
}
output//
enter the string:5
length=1
