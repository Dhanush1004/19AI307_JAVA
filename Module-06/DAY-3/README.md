# Ex.No:6(C)  HIERARCHICAL INHERITANCE 

## AIM:
  To Develop a Java program to perform Hierarchical Inheritance for below scenario Parent have method " display" to display "This is Parent Class". Child1 have method "print" to display "This is Child1 Class" Child1 have method "print" to display "Child2 Class". In Main create object for both child1 and child2 and access its member function.


## ALGORITHM :
1.  Start the Program
2.	Define class `Parent`:
-	a) Method `show()` to print "This is Parent Class"
3.	Define class `Child1` that extends `Parent`:
-	a) Method `print()` to print "This is Child1 Class"
4.	Define class `Child2` that extends `Parent`:
-	a) Method `display()` to print "This is Child2 Class"
5.	In `Main` class `main` method:
-	a) Create `Child1` object `child` and call `show()` and `print()` on it
-	b) Create `Child2` object `chi` and call `show()` and `display()` on it
6.	End

## PROGRAM:
 ```
/*
Program to implement a Hierarchical Inheritance using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
```

## Sourcecode.java:
```
class Parent {
    // Method to display message from Parent class
    public void display() {
        System.out.println("This is Parent Class");
    }
}

// Child1 class inherits from Parent class
class Child1 extends Parent {
    // Method to display message from Child1 class
    public void print() {
        System.out.println("This is Child1 Class");
    }
}

// Child2 class inherits from Parent class
class Child2 extends Parent {
    // Method to display message from Child2 class
    public void print() {
        System.out.println("This is Child2 Class");
    }
}

// Main class to run the program
public class Main {
    public static void main(String[] args) {
        // Creating object for Child1
        Child1 child1 = new Child1();
        
        // Accessing methods from Child1 and Parent
        child1.display(); // Parent class method
        child1.print();   // Child1 class method

        // Creating object for Child2
        Child2 child2 = new Child2();
        
        // Accessing methods from Child2 and Parent
        child2.display(); // Parent class method
        child2.print();   // Child2 class method
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/0ccbeaa4-5bc3-492c-9ea4-8328166d77c4)

## RESULT:
Thus the java program for Hierarchical inheritance was executed successfully.





