# Ex.No:1(D) ARRAYS

## QUESTION:
Write a Java program to print all elements in an array that are greater than a given value

## AIM:
To write a Java program to find and print all elements in an array that are greater than a given value

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named main

Step 4: Inside the main method, create a Scanner object to read input

Step 5: Read the size of the array → store in variable n

Step 6: Declare an array of size n

Step 7: Read n elements from the user and store them in the array

Step 8: Read the target value → store in variable target

Step 9: Initialize a boolean variable flag = false

Step 10: Traverse the array using a loop
- For each element in the array:
    - If element > target:
        - Print the element
        - Set flag = true

Step 11: After the loop, check flag
- If flag == false:
    - Print "No elements greater than target"

Step 12: End the program	

## PROGRAM:
 ```
/*
Program to implement a Array concept using Java
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
        int[] arr=new int[n];
        for(int i=0;i<n;i++){
            arr[i]=sc.nextInt();
        }
        int target=sc.nextInt();
        boolean flag=false;
        for(int i:arr){
            if(i>target){
                flag=true;
                System.out.println(i);
            }
        }
        if(flag==false){
            System.out.println("No elements greater than "+target);
        }
    }
}
```

## OUTPUT:

![alt text](<Screenshot 2026-03-28 103634.png>)

## RESULT:
Thus, the Java program to find and print all elements in an array greater than a given value was successfully executed and verified.