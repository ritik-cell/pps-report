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
