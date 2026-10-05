#include<stdio.h>
int main()
{
int age;
printf("11");
scanf("%d",& age);
if(age>18)
{
printf("eligible to vote");
}
else if (age>15)
{
printf("3 more years to vote");
}
else if (age>10)
{
printf("8 more years to vote");
}
else 
{
printf("not eligible to vote");
}
return 0;
}
