# Ex.No:6(A)  INNER CLASS
## AIM:
To create a Java Program using Method Local Inner Class for below Scenario.
Create a class "Name" with
1. String value "Johnson"
2. Create display() with  a inner class as "Inner"
3. Inner class have print() to display name
In main() access all function using its corresponding Object.

## ALGORITHM :
1. Start
2. Define a class Name
   a. Declare a private instance variable str and initialize it with "Johnson ".
3. Define a method display() inside the Name class
   a. Inside display(), define a local inner class named Inner.
   b. Inside the Inner class:
4. Define a method print() that prints the value of str using System.out.println().
   c. Create an object obj of the Inner class.
   d. Call the print() method using the object obj.
     .Define the main method
   a. Create an object obj1 of class Name.
   b. Call the display() method using obj1.
5. Program Output:
  "Name given in Outer Class is Johnson "
6. End

## PROGRAM:
 ```
/*
Program to implement a Inner Class using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
public class Name
{
    private  String str="Johnson ";
   public void display()
   {
         class Inner
           {
               public void print()
               {
                  System.out.println("Name given in Outer Class is "+str);
               }
           }
           Inner obj=new Inner();
           obj.print();
   }
  
    public static void main(String[] args)
    {
Name obj1=new Name();
obj1.display();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/34abb9d1-c28e-4efd-8f65-a1e456016d83)


## RESULT:
Thus, the Java Program using Method Local Inner Class was executed successfully.

