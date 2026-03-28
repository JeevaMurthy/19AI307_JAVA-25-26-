# Ex.No:1(B) CONDITIONAL STATEMENT


## QUESTION:
A pirate ship has a code lock that only opens if:

- The input code is even, and

    - If it is less than 100, say "Weak Code".

    - If it is between 100 and 999, say "Strong Code".

- If the code is odd, deny access -"Access Denied".


## AIM:
To write a Java program to check whether a given code is even or odd and display appropriate messages using conditional statements.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named main

Step 4: Inside the main method, create a Scanner object to read input

Step 5: Read an integer value from the user → store in variable a

Step 6: Check whether the number is even or odd
- If a % 2 == 0 (even), go to Step 7
- Else, print "Access Denied"

Step 7: If the number is even, check its range
- If a < 100 → print "Weak Code"
- Else if a >= 100 and a < 999 → print "Strong Code"
- Else → print "Access Denied"

Step 8: End the program

## PROGRAM:
 ```
/*
Program to implement a conditional statement using Java
Developed by: JEEVA K
Register Number: 212223230090
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class main{
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        int a=sc.nextInt();
        if(a%2==0){
            if(a<100){
                System.out.println("Weak Code");
            }
            else if(a>=100 && a<999){
                System.out.println("Strong Code");
            }
            else{
                System.out.println("Access Denied");
            }
        }
        else{
            System.out.println("Access Denied");
        }
    }
}
```

## OUTPUT:

![alt text](<Screenshot 2026-03-28 102536.png>)

## RESULT:
Thus, the Java program to verify the pirate ship code using conditional statements was successfully executed, displaying "Weak Code", "Strong Code", or "Access Denied" based on the input.