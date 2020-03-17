![photo](https://raw.githubusercontent.com/ritik-cell/pps-report/master/download%20(1).jpg)

# Programing For Problem Solving(ESC-105)
-----
Submitted By: Ritik Chaudhary

CRN: 1916095

URN: 1905141

Branch: Electrical Engineering (B)

Batch: 2019-2023

-------
Experiment 1: write a code to print hello world.

```
#include<stdio.h>
int main()
{
printf("Ritik");
return 0;
}
```
-------
Experiment 2: Write a code to print big C.

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
Experiment 3: 

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
Experiment 4: Write a code to execute the addition of two numbers
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
Experiment 5: write a code to print smaller number
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
Experiment 6: write a code to print the character in a reverse way
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
Experiment 7: write a code to compute the perimeter and area of a rectangle.
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
Experiment 8: write a code to execute addition of two numbers if the sum is even. 
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



