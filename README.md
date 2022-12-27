/*# The-sum-of-the-cubes-of-the-digits-of-a-3-digit-number-entered-program-to-find-out-if-it-is-equal-to
The sum of the cubes of the digits of a 3-digit number entered program to find out if it is equal to itself*/
#include <stdio.h>
#include <stdlib.h>
int main()
{
// od = ones digit
// td = tens digit
// hd = hundreds digit
int i;
int od, td, hb;
for(i=1; i < 999; i++)
{
     od = i % 10;
     td = (i/10) % 10;
     hd = i / 100;
     od = bb*bb*bb;
     td = ob*ob*ob;
     hd = yb*yb*yb;
     if( i == od+td+hd )
     {
         printf("%d\n",i);
     }
}
return 0;
}
