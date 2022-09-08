# string-functions
This is a program for use of all functions that lie under string library in C programming.

#include <stdio.h>
#include <string.h>

int main()
{
    char s1[] = "Annu";
    char s2[] = "Tannu";
    char s3[10];
    printf("concatenation of two strings is:");
    puts(strcat(s1, s2));
    printf("Reverse of s2 is:");
    puts(strrev(s2));
    printf("Length of string s1 is %d\n", strlen(s1));
    printf("s1 is copied to s3 as:");
    puts(strcpy(s3, s2));
    printf("ASCII comparison of two strings is %d\n", strcmp(s1, s2));
    return 0;
}
