# Ex.No:4(E)  PARAMETERIZED CONSTRUCTOR
## AIM:
To write a parameterized constructor in the Employee class that initializes name and designation, and then call getter methods in the main() method of another class (Sample) to display the values.

## ALGORITHM :

	1.	Start the program.
2.	Define a class Employee:
    a.	  Declare two private string variables: name and designation.
3.	Create a parameterized constructor in Employee:
4.	Accept two parameters: name and designation.
5.	Assign the parameters to the class fields.
6.	Define two getter methods in the Employee class:
     a.	getName() – returns the value of name.
     b.	getDesg() – returns the value of designation.
7.	Create another class Sample with the main method.
8.	Inside the main method:
     a.	Create an object of Employee using the constructor and pass "John" and "Asst.Manager" as arguments.
     b.	Call getName() and store the result in a variable empName.
     c.	Call getDesg() and store the result in a variable empDesg.
9.	Print the values of empName and empDesg.
10.	End the program


## PROGRAM:
 ```
/*
Program to implement a Parameterized Constructor Using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:

```class Employee {
    private String name;
    private String designation;

    // Parameterized Constructor
    public Employee() {
        this.name = "John";
        this.designation = "Asst.Manager";
    }

    public String getName() {
        return name;
    }

    public String getDesg() {
        return designation;
    }
}

public class Sample {
    public static void main(String[] args) {
        // Creating an object of Employee class
        Employee emp = new Employee();

        // Calling methods and storing values
        String empName = emp.getName();
        String empDesg = emp.getDesg();

        // Printing the values
        System.out.println(empName);
        System.out.println(empDesg);
    }
}
```





## OUTPUT:
![image](https://github.com/user-attachments/assets/20b20c36-8079-4c25-b0fd-07df9def9bf1)



## RESULT:
Thus, the  java program was successfully demonstrates the use of a parameterized constructor to initialize class fields.

 


