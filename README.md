#include<stdio.h>
int main()
{
int i=0;
char str[30];
printf("enter the string= ");
gets(str);
while(str[i]!='\0')
{


if(str[i]=='a'|| str[i]=='e'|| str[i]=='i'|| str[i]=='o'|| str[i]=='u'){
printf("%c",str[i]);

}
i++;

}
}
