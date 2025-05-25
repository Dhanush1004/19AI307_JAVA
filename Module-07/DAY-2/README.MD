# Ex.No:7(B) EXCEPTION HANDLING-FINALLY
## AIM:
To Write a Java program to demonstrate control flow of try-catch-finally clause when NumberFormat Exception occur in try block and handled in catch block


## ALGORITHM :
1.	Start the Program
2.	Import `java.util.*` for input handling
3.	Define class `HelloWorld`:
-	a) In `main` method, create `Scanner` object `sc` for input
4.	Use `try` block to:
-	a) Read a string `str` from user input
-	b) Convert `str` to an integer using `Integer.parseInt()` and print the result
5.	Use `catch` block to handle `NumberFormatException`:
-	a) If the string can't be converted to an integer, print the exception message
6.	Use `finally` block to:
-	a) Print "Finally block executed"
7.	After the `try-catch-finally` block, print "Outside try-catch-finally clause"
8.	End

## PROGRAM:
 ```
/*
Program to implement a Exception Handling-Finally using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.*;
public class HelloWorld {
    public static void main(String[] args) 
    {
      Scanner sc=new Scanner(System.in);
       try
        {
           String str=sc.nextLine();
           int a=Integer.parseInt(str);
           System.out.println("Result:" +a);
        }
         
        catch(NumberFormatException ex)
        {
            System.out.println("Exception: " +ex);
        }
         
        finally
        {
            System.out.println("Finally block executed");
        }
         
        // rest program will be executed
        System.out.println("Outside try-catch-finally clause");
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1f9fd324-fd13-443e-9433-665e78d87058)

## RESULT:
Thus the Java program to demonstrate control flow of try-catch-finally clause when NumberFormatException occur in try block and handled in catch block was executed successfully.


