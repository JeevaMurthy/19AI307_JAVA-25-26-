# Ex.No:2(C) ACCESS SPECIFIERS

## QUESTION:
Write a Java program to create a class called Employee with private instance variables employee_id, employee_name, and employee_salary. Provide public getter and setter methods to access and modify the id and name variables, but provide a getter method for the salary variable that returns a formatted string.

## AIM:
To write a Java program demonstrating the use of access specifiers by creating a class Employee with private instance variables and providing public getter and setter methods to access and modify the data safely.

## ALGORITHM :
Step 1: Start the program

Step 2: Import the required package java.util.*

Step 3: Create a class named Employee

Step 4: Declare private instance variables:
- employee_id (int)
- employee_name (String)
- employee_salary (double)

Step 5: Provide public getter and setter methods:
- Getter and setter for employee_id
- Getter and setter for employee_name
- Setter for employee_salary
- Getter method getFormattedSalary() that returns salary as a formatted string (e.g., ₹12345.00)

Step 6: In the main method, create a Scanner object to read input

Step 7: Read employee details from the user:
- employee_id
- employee_name
- employee_salary

Step 8: Create an object of Employee class → e

Step 9: Use setter methods to assign input values to the object

Step 10: Use getter methods to display employee details in a formatted way:
- Print ID, Name, and formatted Salary

Step 11: End the program

## PROGRAM:
 ```
/*
Program to implement a Access Specifiers using Java
Developed by: JEEVA K
Register Number: 212223230090
*/
```

## SOURCE CODE:
```java
import java.util.*;
public class Employee {
    
    private int employee_id;
    private String employee_name;
    private double employee_salary;

    
    public int getEmployeeId() {
        return employee_id;
    }
    public void setEmployeeId(int employee_id) {
        this.employee_id = employee_id;
    }

    
    public String getEmployeeName() {
        return employee_name;
    }
    public void setEmployeeName(String employee_name) {
        this.employee_name = employee_name;
    }

  
    public void setEmployeeSalary(double employee_salary) {
        this.employee_salary = employee_salary;
    }

   
    public String getFormattedSalary() {
        return String.format("₹%.2f", employee_salary);
    }


    public static void main(String[] args){
        Scanner sc=new Scanner(System.in);
        int employee_id=sc.nextInt();
        sc.nextLine();
        String employee_name=sc.nextLine();
        double employee_salary=sc.nextDouble();
        Employee e=new Employee();
        e.setEmployeeId(employee_id);
        e.setEmployeeName(employee_name);
        e.setEmployeeSalary(employee_salary);
        System.out.println("Employee 1");
        System.out.println("ID: "+e.getEmployeeId());
        System.out.println("Name: "+e.getEmployeeName());
        System.out.println("Salary: "+e.getFormattedSalary());
        
    }
}
```

## OUTPUT:

![alt text](<Screenshot 2026-03-28 111012.png>)



## RESULT:
Thus, the Java program demonstrating access specifiers, encapsulation, and formatted salary display was successfully executed and verified.