
# Programming For Problem Solving (ESC-105)
---------
Submitted By: Simran Jassi

Class Roll No: 1916097

University Roll No: 1905156

Branch: Electrical

Section: B

Batch: 2019-2023

----------

               Experiment No: 1
Write a code to print name of the collage.
```C
#include<stdio.h>
int main()
{ 
    puts("Guru Nanak Dev Engineering Collage");
}
```
                Experiment No: 2
Write a code to print the word 'Hello'.
```C
#include<stdio.h>
int main()
{ 
    puts("Hello");
}
```
                Experiment No: 3
Design a code to execute addition of two numbers.
```C
#include<stdio.h>
int main()
{
int a,b,sum;
printf("enter the value of a :");
scanf("%d",&a);
printf("enter the value of b :");
scanf("%d",&b);
sum=a+b;
printf("sum:%d",sum);
}
```
               Experiment No: 4
Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```C
#include<stdio.h>
int main()
{
    int a,b;
    a=100;
    b=250;
    if(a<b)
    {
    printf("100");}
    else
{
printf("250");
}
     }
```
              Experiment No:5
Write a C program to print a big ' C '.
```C
 ######
##    ##
#
#
#
#
#
##    ##
 ######
 ```
 ```C
 #include<stdio.h>
int main()
{
    puts(" ######");
    puts("##    ##");
    puts("#");
    puts("#");
    puts("#");
    puts("#");
    puts("#");
    puts("##    ##");
    puts(" ######");
}
```
                Experiment No: 6
 Design a code to execute addition of two numbers.
```C
#include<stdio.h>
int main()
{
int a,b,sum;
printf("enter the value of a :");
scanf("%d",&a);
printf("enter the value of b :");
scanf("%d",&b);
sum=a+b;
printf("sum:%d",sum);
}
```
                 Experiment No: 7
Write a computer program in C, which takes two numbers (integers) as input and print the smaller number.
```C
#include<stdio.h>
int main()
{
    int a,b;
    a=100;
    b=250;
    if(a<b)
    {
    printf("100");
    }
    else
    {
      printf("250");
     }
}
```
                   Experiment No: 8
Write a C program to print the following character in a reverse way without using any predefined function and header file.
```C
#include<stdio.h>
int main()
{
    char char1;
    char char2;
    char char3;
    scanf("%c%c%c",&char1,&char2,&char3);
    printf("%c%c%c",char3,char2,char1);
}
```
                    Experiment No: 9
Write a C program to compute the perimeter and area of a rectangle with a height of 7 inches and width of 5 inches.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int a,b,perimeter,area;
    a=7;
    b=5;
    perimeter=2*(a+b);
    printf("perimeter of rectangle : %d inches",perimeter);
    area=a*b;
    printf("\n area of the rectangle : %d square inches",area);
}
```
                  Experiment No: 10
Design a code to execute addition of two numbers if the sum is even.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int a,b,sum;
    printf("enter the value of a and b:");
    scanf("%d %d",&a,&b);
    sum=a+b;
    if(sum%2==0)
    {
        printf("Even");
    }
    else
    {
        printf("Odd");
    
    }
}
```
                       Experiment No: 11
 Design a code to mark 'Present' if student entered in a hall before 8:35 and marked 'Late' before 8:45 otherwise marked 'Absent'.If user will enter the time between 8:00 - 8:14 then display a message 'Sorry Gate closed' and if user  will enter the time less than 8:00 then display a message 'Its wrong Time'.
 ```C
 #include<stdio.h>
int main()
{
    float time;
    scanf("%f",&time);
    if(time>8.14 && time<8.36)
    printf("Present");
    else
    { 
        if(time>=8.36 && time<=8.45)
        printf("Late");
        else
        {
            if(time>8.45 && time<9.00)
            printf("Absent");
            else
            {
                if(time==8.00 && time<=8.14)
                printf("Sorry Gate Closed");
                else
                {
                    if(time>7.00 && time<8.00)
                    printf("You entered wrong Time");
                    else
                    {
                        if(time>=9.00)
                        printf("Sorry Gate Closed");
                        else
                        {
                            if(time>=1.00 && time<=7.00)
                            printf("Wrong Timing");
                        }        
                        
            }        
        
        }        
   }
}}}
```
                  Experiment No: 12
Write a code to convert temperature from Fahrenheit scale to centigrade scale.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    float fr,cent;
    printf("enter the temperature in fahrenheit :");
    scanf("%f",&fr);
    cent=5/9*(fr-32);
    printf("TEMPERATURE IN CENTIGRADE : %f",cent);
}
```
                 Experiment No: 13
Write a code to find the factorial of a number.
```C
#include<stdio.h>
#include<math.h>
int main()
{ 
    int a,i,f=1;
    printf("enter the no. ");
    scanf("%d",&a);{
    for(i=1;i<=a;i++)
    f=i*f;}
    printf("factorial of %d = %d",a,f);
}
```
                 Experiment No: 14
Write a code to print table of any number.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int n,i;
    printf("enter the no . ");
    scanf("%d",&n);{
    for(i=1;i<=10;i++)
    printf("\n%d x %d=%d",n,i,n*i);}
}
```
               Experiment No: 15
Write a code to display the number is prime or not.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int i,n,p=0;
    printf("enter no.");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        if(n%i==0)
       { 
           p++;
        }
    }
    if(p==2)
    {
        printf("number is prime");
    }
    else
    {
        printf("number is not prime");
    }
}
```
                  Experiment No: 16
Write a program to swap two numbers using a temporary variable.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int a,b,c;
    printf("enter first no . ");
    scanf("%d",&a);
    printf("enter second no . ");
    scanf("%d",&b);
    c=a;
    a=b;
    b=c;
    printf("\n after swapping first no. is %d",a);
    printf("\n after swapping secong no. is %d",b); 
}
```
                Experiment No: 17
Write a code to print a range of prime number between some range.
```C
#include<stdio.h>
#include<math.h>
int main()
{
    int x,y,count=0,k;
    scanf("%d%d",&x,&y);
    for(int i=x;i<=y;i++)
    {
        for(int k=1;k<=i;k++)
        {
        if(i%k==0)
        count++;
        }
         if (count==2)
         printf("\n%d",i);
         count=0;
    }
        printf("\n");
        return 0;
}
``` 




