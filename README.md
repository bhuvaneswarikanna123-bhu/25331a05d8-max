# 25331a05d8-max
#include <stdio.h>



int main()
{
int a, b, c, max;



printf("Enter three numbers: ");
scanf("%d %d %d", &a, &b, &c);



max = (a > b && a > c) ? a : (b > c ? b : c);



printf("Maximum number is: %d", max);



return 0;
}
