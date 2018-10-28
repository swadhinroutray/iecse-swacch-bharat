# Reading multiple lines of string on scanf

\# include<stdio.h>

int main ()

{

char str[100];

printf("enter the string");

scanf("%[^\t]",str);

printf("the string is :\n");

printf("%s",str);

return 0;

}

