
# EX-01-Datatypes-Operators
## AIM:
Write a C program to read 3 characters one by one and print the characters in a reverse order.

## ALGORITHM:
1.	Declare three character variables to store the input characters.
2.	Use the scanf function to read the characters one by one from the user.
3.	Print the characters in reverse order using the printf function.
4.	End the program.

## PROGRAM:
```python
#include<stdio.h>
int main()
{
    float a=5.800000;
    scanf("%f",&a);
    printf("%f",a);
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/494c065b-3d4c-4002-b46c-016f5ab81d60)


















## RESULT:
Thus the program to read 3 characters one by one and print the characters in a reverse order has been executed successfully.


# EX-02- Conditional-Statements
## AIM:
Write a C program to read A values and check whether A is positive number or not.

# ALGORITHM:
1.	Declare a variable to store the input value A.
2.	Use the scanf function to read the value of A from the user.
3.	Check if the value of A is greater than zero.
4.	If A is greater than zero, print a message indicating that it's a positive number. 
5.	Otherwise, print a message indicating that it's not a positive number.
6.End the program.

# PROGRAM:
```python
#include <stdio.h>
int main()  
{
    int a;
    scanf("%d",&a);
    switch(a)
    {
        case 10:
        printf ("Ten");
        break;
        case 11:
        printf ("Eleven");
        break;
        case 12:
        printf ("Twelve");
        break;
        case 13:
        printf ("Thirteen");
        break;
        case 14:
        printf ("Fourteen");
        break;
        case 15:
        printf ("Fifteen");
        break;
        default:
        printf ("invalid number.");
        
    }
}
```

# OUTPUT:
![image](https://github.com/user-attachments/assets/302b9f3d-1a7a-4195-ac18-39e16aaf8b7f)












# RESULT:
Thus the program to read A values and check whether A is positive number or not has been executed successfully.
 
 
 


# EX-03- Operators-Expressions
## AIM:
Write a program to find minimum between two fraction numbers using conditional operator or ternary operator.

## ALGORITHM:
1.	Declare variables to store the two fraction numbers and the result.
2.	Use the printf function to prompt the user to enter the first fraction number (numerator and denominator separately).
3.	Use the scanf function to read the numerator and denominator of the first fraction.
4.	Repeat steps 2 and 3 to get the second fraction from the user.
5.	Calculate the decimal values of both fractions by dividing the numerators by the denominators.
6.	Use the conditional (ternary) operator to compare the decimal values and store the minimum value in the result variable.
7.	Print the minimum value.

## PROGRAM:
```python
#include <stdio.h>
#include<math.h>
int main()
{
    float principle,rate,year,CI;
    scanf("%f",&CI);
    scanf("%f",&year);
    scanf("%f",&rate);
    principle = CI/(pow((1 + (rate/100)),year));
    printf("Principle Amount is = %.2f",principle);
    
}
```
## OUTPUT:
![image](https://github.com/user-attachments/assets/96e97374-42dc-4960-b67f-9868b6975aa8)










## RESULT:
Thus the program to find minimum between two fraction numbers using conditional operator or ternary operator has been executed successfully.




# EX-04- Using Conditional Statements

## AIM:
Write a C program to check whether the input value is equal to 1 using simple if statement

## ALGORITHM:
1.	Declare a variable to store the input value.
2.	Use the scanf function to read the input value from the user.
3.	Use an if statement to check if the input value is equal to 1.
4.	If the condition in the if statement is true, print a message indicating that the input value is equal to 1.
5.	Otherwise, print a message indicating that it's not equal to 1.
6.	End the program.

## PROGRAM:
```python
#include <stdio.h>
int main()  
{
    int a,b,c;
    scanf("%d%d%d",&a,&b,&c);
    if(a>b)
    {
    printf("A is largest");
    }
    else if(b>c)
    {
        printf("B is largest");
    }
    else if(c>a)
    {
        printf("C is largest");
    }
    else
    printf("A, B, C are equal");
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/a01d0614-d8db-4078-8a9e-d0b11b2d8c13)










	

## RESULT:
Thus the program to check whether the input value is equal to 1 using simple if statement has been executed successfully



# EX-05- Calculating Total, Percentage, And Division Using Conditional Statements 
## AIM:
To write a C program that reads marks of three subjects, calculates the total and percentage, and then determines the division (First, Second, Pass, or Fail) based on the percentage and minimum marks criteria.
## ALGORITHM:
1.	Start
2.	Declare integer variables m1, m2, m3 for marks, and float variables tot, per.
3.	Input the marks for three subjects.
4.	Calculate total marks: tot = m1 + m2 + m3
5.	Calculate percentage: per = tot / 3
6.	Display total and percentage.
7.	Check if all marks are greater than or equal to 40:
8.	If yes:
a.	If percentage >= 60: Print “Division = First”
b.	Else if percentage >= 48: Print “Division = Second”
c.	Else if percentage >= 36: Print “Division = Pass”
9.	Else: Print “Division = Fail”
10.	End
## PROGRAM:
```python
#include <stdio.h>
int main()
{
    int s1,s2,s3,s4,s5,s6;
    float total,average,percentage;
    scanf("%d%d%d%d%d%d",&s1,&s2,&s3,&s4,&s5,&s6);
    scanf("%f%f%f",&total,&average,&percentage);
    total=s1+s2+s3+s4+s5+s6;
    printf("Total marks = %.2f",total);
    average=total/6;
    printf("\nAverage marks = %.2f",average);
    percentage=total/6;
    printf("\nPercentage = %.2f",percentage);
    return 0;
    
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/ab986fc5-cece-4409-8a17-0a55a3ac7cc5)

## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

