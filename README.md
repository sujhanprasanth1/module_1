# Program-1-a
## C-Module 1
## EX_NO-01)a)-Datatypes-Operators
### Date: 06-09-2025
### Name: Sujhan Prasanth S B
### Register Number:25018059
## AIM:
Write a C program to read a float value from the user and to display the same value.
## ALGORITHM:
1. Start the program.
2. Declare a float variable to store the input value.
3. Read the float value from the user using the scanf function.
4. Print the float value using the printf function with two decimal places (%.2f).
5. End the program.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    float num;
    scanf("%f",&num);
    printf("%.2f",num);
    return 0;
}
```
## OUTPUT:
<img width="850" height="288" alt="Screenshot 2025-10-19 201433" src="https://github.com/user-attachments/assets/92963594-8d95-4ed9-884b-e17426d5d477" />

## RESULT:
Thus the program to read a float value from the user and to display the same value has been executed successfully
# Program-1-b
## C-Module 1
## EX_NO-01)b)-Conditional Statements
### Date: 06-09-2025
### Name: Sujhan Prasanth S B
### Register Number:25018059
## AIM:
Write a C program to read A values and check whether the value is greater than and equal to 100. 
## ALGORITHM:
1. Start the program.
2. Declare an integer variable to store the input value.
3. Read the integer value from the user using the scanf function.
4. Check if the value is greater than or equal to 100.

   a. If true, print "The Value is greater than or equal to 100".

    b. If false, do nothing (or skip printing).
6. End the program.
## PROGRAM:
```
#include <stdio.h>
int main()
{
    int num;
    scanf("%d",&num);
    if(num>=100){printf(
        "The Value is greater than or equal to 100");}
    
 return 0;   
}
```
## OUTPUT:
<img width="1169" height="408" alt="Screenshot 2025-10-19 203624" src="https://github.com/user-attachments/assets/57566734-83c5-4b20-b565-ba555c8d1a34" />


## RESULT:
Thus the program to read A values and check whether the value is greater than and equal to 100
has been executed successfully
# Program-1-c
## C-Module 1
## EX_NO-01)c)-Operators & Expressions
### Date: 06-09-2025
### Name: Sujhan Prasanth S B
### Register Number:25018059
## AIM:
Write a program to find principle amount based on simple interest, time & rate of interest. 
## ALGORITHM:
1. Start the program.
2. Declare three float variables to store simple interest, time, and rate of interest.
3. Read the values of simple interest, time, and rate from the user using the scanf function.
4. Declare a float variable to store the principle amount.
5. Calculate the principle amount using the formula: 

       Principle = (Simple Interest) / (Time * Rate) * 100

6. Print the principle amount using the printf function with two decimal places.
7. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    float sint;
    float time;
    float rate;
    scanf("%f %f %f",&sint,&time,&rate);
    float pri;
    pri=sint/(time*rate);
    pri=pri*100;
    printf("Principle amount is = %.2f",pri);
    return 0;
}
```
## OUTPUT:

<img width="1182" height="321" alt="Screenshot 2025-10-19 204817" src="https://github.com/user-attachments/assets/21f38db1-187e-40b9-b859-b1616b8f43f7" />


## RESULT:
Thus the program to find principle amount based on simple interest, time & rate of interest has been executed successfully
# Program-1-d
## C-Module 1
## EX_NO-01)d)-Conditional Statements
### Date: 06-09-2025
### Name: Sujhan Prasanth S B
### Register Number:25018059
## AIM:
Write a C program to read a, b values and check whether  a equal to b. 
## ALGORITHM:
1. Start the program.
2. Declare two integer variables to store the input values.
3. Read the two integer values from the user using the scanf function.
4. Check if the first value is equal to the second value.

    a. If true, print "a is equal to b".

   b. If false, do nothing (or skip printing).

6. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
int a,b;
scanf("%d %d",&a,&b);
if(a==b)
printf("a is equal to b");
 return 0;   
}
```
## OUTPUT:
<img width="842" height="345" alt="Screenshot 2025-10-19 213358" src="https://github.com/user-attachments/assets/a4cf864d-9e76-486a-9e18-0d8616d4cc10" />

## RESULT:
Thus the program to read a, b values and check whether  a equal to b has been executed successfully
# Program-1-e
## C-Module 1
## EX_NO-01)e)-Datatypes & Operators
### Date: 06-09-2025
### Name: Sujhan Prasanth S B
### Register Number:25018059
## AIM:
Write a C program to find the ASCII value of a given character.
## ALGORITHM:
1. Start the program.
2. Declare a character variable to store the input character.
3. Read the character from the user using the scanf function.
4. Print the ASCII value of the character using the printf function.
5. End the program.

## PROGRAM:
```
#include <stdio.h>
int main()
{
    char ch;
    scanf("%c",&ch);
    printf("ASCII value of %c is %d",ch,ch);
    return 0;
}
```
## OUTPUT:
<img width="851" height="344" alt="Screenshot 2025-10-19 213922" src="https://github.com/user-attachments/assets/d3a0cc60-dbff-4f5f-b1b3-0d6736dae154" />

## RESULT:
Thus the program to find the ASCII value of a given character has been executed successfully
