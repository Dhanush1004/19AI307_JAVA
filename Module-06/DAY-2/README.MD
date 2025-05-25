# Ex.No:6(B) MULTI-LEVEL INHERITANCE

## AIM:
To Develop a Java program to perform Multilevel Inheritance to calculate the area of circle..

## ALGORITHM :
1.	Start the Program.
2.	Define class `Shapes`:
-	a) Method `print_shape()` to print "Shapes Class"
3.	Define class `Circle` that extends `Shapes`:
-	a) Declare integer `rad`
-	b) Method `get()` to read `rad` from user input
4.	Define class `Area` that extends `Circle`:
-	a) Method `cal()` to calculate `result = 3.14 * rad * rad` and print "Area of Circle is " followed by `result`
5.	In `Main` class `main` method:
-	a) Create `Area` object `obj`
-	b) Call `print_shape()`, `get()`, and `cal()` on `obj` to display shape type, read radius, and calculate area
6.	End


## PROGRAM:
 ```
/*
Program to implement a MultiLevel Inheritance using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.Scanner;

// Base class
class Shapes {
    // Method to display class name
    public void print_Shape() {
        System.out.println("Shapes Class");
    }
}

// Class Circle that extends Shapes
class Circle extends Shapes {
    // Variable to store radius
    protected double radius;

    // Method to get radius from the user
    public void get() {
        Scanner scanner = new Scanner(System.in);
        radius = scanner.nextDouble();
    }
}

// Class Area that extends Circle
class Area extends Circle {
    // Method to calculate and display area of the circle
    public void calc() {
        double area = 3.14 * radius * radius;
        System.out.println("Area of Circle is " + area);
    }
}

// Main class
public class Main {
    public static void main(String[] args) {
        // Create object of Area class
        Area areaObj = new Area();

        // Access methods
        areaObj.get();          // Input radius
        areaObj.print_Shape();  // Display Shapes Class
        areaObj.calc();         // Calculate and display area
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/5068a0f2-8e7a-4376-8be8-791f56836439)

## RESULT:
Thus the java program for multi-level inheritance was executed successfully.




