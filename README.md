/*# Finding-Number-of-Digits
Finding Number of Digits/*
#include <conio.h>
#include <stdio.h>
    int main()
{
    int num1,i=1;
    printf("Enter the number: ");
    scanf("%d",&num1);
    while(num1>=10)
    {
        num1/=10;
        i++;
    }
    printf("\nThe place value of the number is %d\n",i);
}
