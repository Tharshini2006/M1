NAME : THARSHINI.M
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
#include <stdio.h>
int main()
{
    char ch1, ch2, ch3;
    printf("Enter first character: ");
    scanf(" %c", &ch1);
    printf("Enter second character: ");
    scanf(" %c", &ch2);
    printf("Enter third character: ");
    scanf(" %c", &ch3);
    printf("Characters in reverse order: %c %c %c\n", ch3, ch2, ch1);
    return 0;
}
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/506dc3fb-b265-4461-af49-4a7500783b9f)




















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
    int A;
    printf("Enter a value: ");
    scanf("%d", &A);
    if (A > 0)
    {
       printf("%d is a positive number.\n", A);
    }
   else
   {
       printf("%d is not a positive number.\n", A);
   }
return 0;
}


```

# OUTPUT:
![image](https://github.com/user-attachments/assets/90f02747-ccd8-4950-850a-6f98abd15403)















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
int main()
{
     int a,b;
     scanf("%d%d",&a,&b);
     if (a<b)
     {
         printf("Minimum between %d and %d is %d",a,b,a);
     }
    else
    {
        printf("Minimum between %d and %d is %d",a,b,b);
    }

return 0;
}

```
## OUTPUT:
![image](https://github.com/user-attachments/assets/81fc3c21-1977-45c6-bc6a-a418e6fd7076)












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
int main(){
    int a;
    scanf("%d",&a);
    if(a==1)
    printf("TRUE");
}

  
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/d39255cf-4545-4250-a08b-cd93dff61afd)












	

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
#include <string.h>
int main()
{
    int phy,che,ca,total;
    float per;
    char div[10];
    scanf("%d%d%d",&phy,&che,&ca);
    total = phy+che+ca;
    per = total/3.0;
    if (per>=60)
    strcpy(div,"First");
    else if (per<60&&per>=48)
    strcpy(div,"Second");
    else if (per<48&&per>=36)
    strcpy(div,"Pass");
    else
    strcpy(div,"Fail");
     printf("Total Marks = %d\nPercentage = %5.2f\nDivision = %s\n",total
     return 0;
}

    
```

## OUTPUT:
![image](https://github.com/user-attachments/assets/1d2e6134-e72f-4d23-8579-09a1009d847f)

![image](https://github.com/user-attachments/assets/5c663ceb-165c-4cef-a005-95c495b98032)





## RESULT:
The program successfully takes three subject marks, calculates the total and percentage, and correctly determines the division based on predefined grading logic.

