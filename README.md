/*# The-sum-of-the-cubes-of-the-digits-of-a-3-digit-number-entered-program-to-find-out-if-it-is-equal-to
The sum of the cubes of the digits of a 3-digit number entered program to find out if it is equal to itself*/
#include <conio.h>
#include <stdio.h>
    int main()
{
    int dig,num,sum=0;
    printf("Enter 3 digit number: ");scanf("%d",&num);
    dnz:
    dig=num%10;
    sum+=pow(dig,3);
    num/=10;
    if(num<10)

    {
        sum+=pow(num,3);
        goto dnz;
    }
    if(num=sum)
        printf("Equal");
    else
        printf("Not equal");

}
