# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Lovely is learning java basics, can you teach her the different types of datatypes in java? Write a program that uses all datatypes and print them all.

Input Format:

byte - 24

short - 11000

int - 1,34,500

long - 24,23,10,34

float - 24.20

double - 1,30,000.80

boolean - true/false

char - 'u'

String -"Heyyy, Lovely, Let's learn java!"

## AIM:

The aim of this program is to understand and demonstrate the different data types in Java by declaring variables of each type, assigning values to them, and printing them to the console.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package (java.util.*)

Step 3: Create a class named main

Step 4: Inside the main method, create a Scanner object to read input from the user

Step 5: Read different types of inputs from the user:

- Read a byte value → store in variable a
- Read a short value → store in variable b
- Read an int value → store in variable c
- Read a long value → store in variable d
- Read a float value → store in variable e
- Read a double value → store in variable f
- Read a boolean value → store in variable g
- Read a char value → store in variable h
- Read a String value → store in variable str

Step 6: Display a heading message

Step 7: Print all the values with appropriate labels:

- Print byte value
- Print short value
- Print int value
- Print long value
- Print float value
- Print double value
- Print boolean value
- Print char value
- Print string value

Step 8: End the program



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: Jeeva K
RegisterNumber:  212223230090
*/
```

## Sourcecode.java:

```java
import java.util.*;
public class main{
    public static void main(String args[]){
        Scanner sc = new Scanner(System.in);
        byte a = sc.nextByte();
        short b = sc.nextShort();
        int c = sc.nextInt();
        long d = sc.nextLong();
        float e = sc.nextFloat();
        double f = sc.nextDouble();
        boolean g =sc.nextBoolean();
        char h = sc.next().charAt(0);
        sc.nextLine();
        String str = sc.next();
        System.out.println("Hey Lovely, let's print all types of data received from user using different data types");
        System.out.println("This is byte datatype "+a);
        System.out.println("This is short datatype "+b);
        System.out.println("This is int datatype "+c);
        System.out.println("This is long datatype "+d);
        System.out.println("This is float datatype "+e);
        System.out.println("This is double datatype "+f);
        System.out.println("This is boolean datatype "+g);
        System.out.println("This is char datatype "+h);
        System.out.println("This is string datatype "+str);
    }
}
```





## OUTPUT:

![alt text](<Screenshot 2026-03-28 101628.png>)

## RESULT:

Thus, the Java program demonstrating different data types and user input using the Scanner class was successfully executed and verified.