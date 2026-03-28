# Ex.No:1(C) LOOPING STATEMENT

## QUESTION:
In mathematics, the factorial of a non-negative integer n, denoted as n!, is the product of all positive integers less than or equal to n. For example:

- 5! = 5 × 4 × 3 × 2 × 1 = 120

- 3! = 3 × 2 × 1 = 6

- 0! is defined as 1.

Write a Java program that prompts the user to enter a non-negative integer and then calculates and displays the factorial of the given number.

- Use a for loop to perform the calculation.

- Make sure to handle the case when the user enters 0.

- Display the result in a clear and user-friendly way.
## AIM:
To write a Java program to calculate the factorial of a non-negative integer using a for loop.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named main

Step 4: Inside the main method, create a Scanner object to read input

Step 5: Read a non-negative integer from the user → store in variable n

Step 6: Initialize a variable fact = 1

Step 7: Check if n == 0 or n == 1
If true, factorial is 1

Step 8: Else, calculate factorial using a loop
- Run a loop from i = 1 to n
- Multiply fact = fact * i in each iteration

Step 9: Display the result
- Print: "Factorial of n is: fact"

Step 10: End the program


## PROGRAM:
 ```
/*
Program to implement a Looping Statement using Java
Developed by: JEEVA K
Register Number: 212223230090
*/
```

## SOURCE CODE:

```java
import java.util.*;
public class main{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        int n=sc.nextInt();
        int fact=1;
        if(n==0 && n==1){
            System.out.println("Factorial of "+n+" is: 1");
        }
        else{
            for(int i=1;i<=n;i++){
                fact=fact*i;
            }
            System.out.println("Factorial of "+n+" is: "+fact);
        }
    }
}
```

## OUTPUT:

![alt text](<Screenshot 2026-03-28 103336.png>)

## RESULT:
Thus, the Java program to calculate the factorial of a non-negative integer using a for loop was successfully executed and verified.