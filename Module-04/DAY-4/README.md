# Ex.No:4(D) FINAL & STATIC IN JAVA

## AIM:
   To create a Java program to perform final & static keyword for below situation Employee object contains member 'Emp_Id'. It contains object named name, which contains its own informations such as Fname, Mname, Lname.
 
## ALGORITHM :
1.	Start the Program.
2.	Define class `Name`:
-	a) Declare three `String` variables: `Fname`, `Mname`, and `Lname`
-	b) Define method `dispName(String fn, String mn, String ln)`:
-	i) Print the full name using the passed parameters `fn`, `mn`, and `ln`
3.	Define class `Employee`:
-	a) Declare an integer variable `Emp_Id`
-	b) Create an instance of `Name` called `obj`
-	c) Define method `disp(int id)`:
-	i) Print the employee ID
-	ii) Create a new `Name` object and call `dispName("B", "Leo", "John")` to display the name
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `emp.disp(101)` to display the employee details
5.	End






## PROGRAM:
 ```
/*
Program to implement a final & Static using Java
Developed by: A.DHANUSH
RegisterNumber:  212222220010
*/
```

## Sourcecode.java:
```
class Name {
    String Fname;
    String Mname;
    String Lname;

    Name(String fname, String mname, String lname) {
        this.Fname = fname;
        this.Mname = mname;
        this.Lname = lname;
    }

    void display() {
        System.out.println("First Name: " + Fname);
        System.out.println("Middle Name: " + Mname);
        System.out.println("Last Name: " + Lname);
    }
}

class Employee {
    final int Emp_Id;           // final keyword: cannot be changed once assigned
    Name name;                  // object of Name class
    static String company = "ABC Corp";  // static variable shared by all Employee objects

    Employee(int empId, Name name) {
        this.Emp_Id = empId;
        this.name = name;
    }

    void display() {
        System.out.println("Employee ID: " + Emp_Id);
        name.display();
        System.out.println("Company: " + company);
    }
}

public class Main {
    public static void main(String[] args) {
        Name empName = new Name("Dhanush", "A", "Kumar");
        Employee emp = new Employee(101, empName);
        emp.display();
    }
}


```





## OUTPUT:
```Employee ID: 101
First Name: Dhanush
Middle Name: A
Last Name: Anbu
Company: ABC Corp
```



## RESULT:
Thus, the java program to perform final & static keyword was executed successfully.
