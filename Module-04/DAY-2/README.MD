# Ex.No:4(B) INTRODUCTION TO JAVA INHERITANCE

## AIM:
To create  a Java program to perform the inheritance concept for employee details.

## ALGORITHM :
1.	Start the Program
2.	Define class `Person`:
-	a) Declare `emp_id`, `name`, and `dept` as instance variables
3.	Define class `Employee` that extends `Person`:
-	a) Define method `getDetails()`:
-	i) Create a `Scanner` object `sc`
-	ii) Read `name`, `emp_id`, and `dept` from user input
-	b) Define method `display()`:
-	i) Print the `name`, `emp_id`, and `dept`
4.	Define `Main` class with `main` method:
-	a) Create an `Employee` object `emp`
-	b) Call `getDetails()` to input employee details
-	c) Call `display()` to output employee details
5.	End








## PROGRAM:
 ```
/*
Program to implement a Inheritance using Java
Developed by: 
RegisterNumber:  
*/
```

## Sourcecode.java:
```

class Subject
{
    
    String subject1,subject2,subject3,subject4;
      //Write Your Code Here
      
    void dispSub(String subject1,String subject2,String subject3,String subject4)
    {
        System.out.println(subject1+" "+subject2+" "+subject3+" "+subject4);
         //Write Your Code Here
    }
}
class Student
{
    int Stu_Id;
    Subject obj = new Subject();
    
    //Write Your Code Here
    
    void disp(int id)
    {
        System.out.println(id);
        obj.dispSub("B.Tech","IT","Third","year");
        //Write Your Code Here
    }
}

public class Main
{
    public static void main(String[] args)
    {
        //Write Your Code Here
        Student obj = new Student();
        obj.disp(101);
        
    }
}
```


## OUTPUT:
```

Input      Expected                 Got
---        101                      101
           B.Tech IT Third year     B.Tech IT Third year
```



## RESULT:
Thus the Java program to implement the inheritance concept for employee details was  executed successfully.

