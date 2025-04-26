# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: 
RegisterNumber:  
*/
```

# Ex.No:1(E)  STATIC VARIABLE

## AIM:
To write a Java program to print student details (name and age), where age is the same for all students. Use a static variable to represent the age and demonstrate its use in accessing a shared value across all class objects

## ALGORITHM :
1.	Start the program.
2.	Create a class named Student.
3.	Declare a static variable age in the Student class.
4.	Declare an instance variable name.
5.	Create a constructor to initialize the student's name.
6.	Define a method displayDetails() to print the student's name and age.
7.	In the main method:
I.	Assign a value to the static variable age.
II.	Create multiple Student objects with different names.
III.	Call the displayDetails() method for each student.
8.	End the program.



## PROGRAM:
 ```
/*
Program to implement a Static Variable using Java
Developed by: A.DHANUSH
RegisterNumber: 212222220010
*/
```

## Sourcecode.java:
```java
import java.util.*;
public class Demo
{
    static String age="18";
    String name;
	public static void main(String[] args) {
	Scanner sc=new Scanner(System.in);
	Demo obj1=new Demo();
	Demo obj2=new Demo();
	obj1.name=sc.next();
	obj2.name=sc.next();
	System.out.println("Student name: "+obj1.name+"Age: "+age);
	System.out.println("Student name: "+obj2.name+"Age: "+age);
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/7778b959-2267-43c2-9873-39062ae1a2d7)


## RESULT:
Thus, the Java program for the concept of using a static variable for shared data was correctly implemented and verified successfully. 


