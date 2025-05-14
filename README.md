# print-patterns.c
// C program to print pattern  Z ZY ZYX ZYXW ZYXWV 

Z
ZY
ZYX
ZYXW
ZYXWV

#include <stdio.h>

int main() {
    int i,j;
    for(i=0;i<5;i++)
    {
        for(j=0;j<=i;++j)
        printf("%c",90-j);
        printf("\n");
    }
    return 0;
}
