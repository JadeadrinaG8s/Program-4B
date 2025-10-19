# Program-4B
C module 4
EX NO-4)B)a C program to input number from the user and check whether the number is even or odd using a switch case. 
DATE:19/10/25
NAME:JADE ADRINA J
REF NO:25017000
AIM:TO Write a C program to input number from the user and check whether the number is even or odd using a switch case. 
ALGORITHM:
1)Take a number as input from user.2)check if number is divisible by 2.3)if divisible ,print even using printf() function.
PROGRAM:
```
#include<stdio.h>
int main()
{
    int ch,k;
    scanf("%d",&ch);
    if (ch%2==0){
        k= 0;
    }
    else
    {
        k= 1;
    }
    switch(k){
        case 0:
        printf("Number is Even");
        break;
        case 1:
        printf("Number is Odd");
        break;
    }
    
}
```
OUTPUT:
<img width="792" height="221" alt="Screenshot 2025-10-19 230912" src="https://github.com/user-attachments/assets/56d8ec31-7cde-492e-905f-29563cec06a6" />
RESULT:
THUS,A a C program to input number from the user and check whether the number is even or odd using a switch case has been executed successfully.


