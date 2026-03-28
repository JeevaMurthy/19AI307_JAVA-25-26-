# Ex.No:1(E) STRINGS AND MATH FUNCTION

## QUESTION:
Write a java program to remove duplicate characters from a string.

## AIM:
To write a Java program to remove duplicate characters from a given string using string functions.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named main

Step 4: Inside the main method, create a Scanner object to read input

Step 5: Read a string from the user → store in variable str

Step 6: Initialize an empty string result = ""

Step 7: Traverse the string using a loop
- For each character in str:
    - Store character in variable ch
    - Check if ch is already present in result using indexOf()
    - If not present (indexOf(ch) == -1):
        - Append ch to result

Step 8: Display the result
- Print: "String after removing duplicates: " + result

Step 9: End the program

## PROGRAM:
 ```
/*
Program to implement a Strings and Math Function using Java
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
        String str=sc.next();
        String result="";
        for(int i=0;i<str.length();i++){
            char ch=str.charAt(i);
            if(result.indexOf(ch) == -1){
                result=result+ch;
            }
        }
        System.out.println("String after removing duplicates: "+result);
        
    }
}
```

## OUTPUT:

![alt text](<Screenshot 2026-03-28 104659.png>)



## RESULT:
Thus, the Java program to remove duplicate characters from a string using string functions was successfully executed and verified.