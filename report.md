![photo](https://raw.githubusercontent.com/ritik-cell/pps-report/master/download%20(1).jpg)

# Programing For Problem Solving(ESC-105)
-----
Submitted By: Ritik Chaudhary

CRN: 1916095

URN: 1905141

Branch: Electrical Engineering (B)

Batch: 2019-2023

-------
Program 1: write a code to print hello world.

```
#include<stdio.h>
int main()
{
printf("Ritik");
return 0;
}
```
-------
Program 2: Write a code to print big C.

```
#include <stdio.h>
int  main()
{
    int i=0;
    for(i=0;i<9;i++)
    {
        if(i==0 || i==8)
        printf(" ######\n");
        else if(i==1 || i==7)
        printf("##    ##\n");
        else
        printf("#\n");
    }
```
-------
Program 3: 

```
#include <stdio.h>
int main ()
{
    printf("########    ########    ####     ####\n");
    printf("##      ####        #### ###    ###\n");
    printf("##      ####        ####   ### ###\n");
    printf("######  ####        ####    ####\n");
    printf("##      ####        ####   ### ###\n");
    printf("##      ####        ####  ###   ###\n");
    printf("##          ########    ####    ####\n");
    
    return 0;
}
```
---------
Program 4: Write a code to execute the addition of two numbers
```
#include <stdio.h>
int main()
{
    int x,y,z;
    scanf("%d %d",&x,&y);
    z=x+y;
    printf("%d",z);
    
    return 0;
}
```
------------
Program 5: write a code to print smaller number
```
#include<stdio.h>
int main()
{
    int x,y;
    scanf("%d %d",&x,&y);
    if(x<y)
    printf("%d",x);
    else
    printf("%d",y);
    
    return 0;
    
}
```
--------------
Program 6: write a code to print the character in a reverse way
```
#include<stdio.h>
int main()
{
    char ch1;
    char ch2;
    char ch3;
    scanf(" %c %c %c",&ch1,&ch2,&ch3);
    printf(" %c %c %c",ch3,ch2,ch1);
    
    return 0;
}
```
-----------
Program 7: write a code to compute the perimeter and area of a rectangle.
```
#include<stdio.h>
int main()
{
    int width;
    int height;
    int perimeter;
    int area;
    scanf("%d %d",&height,&width);
    perimeter=2*(height+width);
    printf("Perimeter of the rectangle: %d inches\n",perimeter);
    area=height*width;
    printf("Area of the rectangle = %d square inches",area);
    
    
    return 0;
}
```
----------------
Program 8: write a code to execute addition of two numbers if the sum is even. 
```
#include<stdio.h>
int main ()
{
    int x,y,z;
    scanf("%d %d",&x,&y);
    z=x+y;
    if(z%2==0)
    printf("even");
    else
    printf("odd");
    
    return 0;
}
```
--------------
Program 9: write a code to check Timming.
```
#include<stdio.h>
int main ()
{
    float time;
    scanf("%f"&time);
    if(time>8.14 || time<8.36)
    printf("present");
    else
    {
        if(time>=8.36 || time<=8.45)
        printf("Late");
        else
        {
            if(time>8.45 || time<9.00)
            printf("Absent");
            else
            {
                if(time==8.00 || time<=8.14)
                printf("sorry gate closed");
                else
                {
                    if(time>7.00 || time<8.00)
                    printf("You entered wrong time");
                    else
                    {
                        if(time>=9.00)
                        printf("sorry gate closed");
                        else
                        {
                            if(time>=1.00 || time<=7.00)
                            printf("wrong timing");
                        }
                    }
                }
            }
        }
    }
}
```
---------
Program 10: write a code to convert temperature from Fahrenheit scale to centigrade.
```
#include<stdio.h>
int main()
{
    int f,c;
    scanf("%d",&f);
    c=5*(f-32)/9;
    printf("Fahrenheit scale: %d\n",f);
    printf("Centigrade scale: %d",c);
    
    return 0;
}
```
--------------
Program 11: Write a code to find the factorial of a number.
```
#include<stdio.h>
int main ()
{
    int i,n,f=1;
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    f=f*i;
    printf("Factorial of %d is %d",n,f);
    
    return 0;
}
```
-----------
Program 12: Write a code to display a sum of series without using predefined function and header file.
```
#include<stdio.h>
int main()
{
    int n,i,x;
    scanf("%d",&n);
    scanf("%d",&x);
    for(i=1;i<=n;i++)
    printf("sum of series :%d^%d",x,n);
    return 0;
}
```
--------
Program 13(MSE 1) :Write a computer program in C, to print nth term, and sum up to nth term for series:

x−x^3/3!+x^5/5!−x^7/7!+x^9/9!−⋯

where "1" represent factorial.

No user made function or library function is to be used.
````C
#include<stdio.h>
int main()
{
int x,n;
printf("\nThe series is : x-x^3/3!+x^5/5!-......");
printf("\nEnter the value of x and n:");
scanf("%d %d",&x,&n);
int i,m;
float sum=0,a,b,c;
for(i=1;i<=n;i++)
   {
   m=((2*1)-1);
   a=pow(x,m);
   b=fact(m);
   c=a/b;
   if(i%2==0)
   sum=sum-c;
   else
   sum=sum+c; 
   }
printf(" thye nth term is %d^%d/%d!",x,m,m);   
printf(" the sum of nth term is %0.3f\n",sum);
return 0;
}

int pow(int a,int b)
{
int p=1,i=1;
while(b!=0)
   {
    p=p*a;
    b--;
   }
return (p);
}

int fact(int n)
{
int i,f=1;
for(i=n;i>1;i--)
  {
   f=f*i;
  }
return (f);
}
```
------------
Program 14(MSE 1) :Write a computer program in C, which take integer input from user. If entered value > 10, it will call a function, which prints multiplication table of of entered number, from 1 to 10, in following format:

1 x 7 = 7

2 x 7 = 14

`````
If entered value is between 6 to 10, then will be call another function, which print number of lines equal to entered number in following pattern:

    #
   #.#
  #...#
 #.....#
#.......#
`````

for any other input it will display:

Have a nice day!
```
#include<stdio.h>
int main()
{
int num;
printf("\n\tEnter a number\n");
scanf("%d",&num);
if(num>10)
  {
int table();
 table(num);
  }
else
  {
  if(num>=6 && num<=10)
   {
int pattern();
  pattern(num);
   }
   else
   {
 void print();
print();
   }
  }
return 0;
}
   
int table(int a)
{
int i,table;
for(i=1;i<=10;i++)
printf("%d X %d=%d \n",i,a,i*a);
}
  
  int pattern(int b)
  {
  int i,j;
  for(i=1;i<=b;i++)
  {
  for(j=1;j<=b;j++)
    {
  if(j==1 || j==i)
   printf("*");
  else
   if(j>=2 && j<=i-1)
   printf(".");
  else
  printf(" "); 
  }
  printf("\n");
 }
}
  
void print()
{
printf("Have a nice day!");
 }
 ```
 ----------
