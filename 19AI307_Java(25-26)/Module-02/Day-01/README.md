# Ex.No:2(A) CLASS AND OBJECT

## QUESTION:
Create a class Book with attributes title, author, price. Create 2 objects and print their details.
## AIM:
To create a class Book with attributes title, author, and price, create two objects of the class, and display their details.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named Book
- Declare attributes: title (String), author (String), price (double)

Step 4: Create a Main class with the main method

Step 5: Inside main, create a Scanner object to read input

Step 6: Create the first object of Book class → b1
- Read input for title, author, and price and assign to b1

Step 7: Create the second object of Book class → b2
- Read input for title, author, and price and assign to b2

Step 8: Print the details of both objects in a user-friendly format

Step 9: Close the Scanner object

Step 10: End the program

## PROGRAM:
 ```
/*
Program to implement a Class and Objects using Java
Developed by: JEEVA K
Register Number: 212223230090
*/
```

## SOURCE CODE:
```java
import java.util.Scanner;

class Book{
    String title;
    String author;
    double price;
}
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);

        Book b1 = new Book();
        b1.title = sc.next();
        b1.author = sc.next();
        b1.price = sc.nextDouble();

        Book b2 = new Book();
        b2.title = sc.next();
        b2.author = sc.next();
        b2.price = sc.nextDouble();

        System.out.println(b1.title + " | " + b1.author + " | Rs." + b1.price);
        System.out.println(b2.title + " | " + b2.author + " | Rs." + b2.price);

        sc.close();
    }
}

```


## OUTPUT:

![alt text](<Screenshot 2026-03-28 105636.png>)


## RESULT:
Thus, the Java program to create a class Book, instantiate two objects, and display their details was successfully executed and verified.