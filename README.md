//program to check vowel or not
//input:a 
//output :a is a vowel
#include<stdio.h>
int main() 
{
char ch;
Printf("enter the alphabet:");
scanf("%c", &ch);
switch(ch) 
case'a':
case'e':
case'i':
case'o':
case'u':
case'A':
case'E':
case'I':
case'O':
case'U':
printf("%c is a vowel",ch);
break;
default;
printf("%c is not vowel",ch);
}
Return (0);
}




