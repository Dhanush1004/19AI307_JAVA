# Ex.No:4(C)    CONSTRUCTOR CHAINING(SUPER KEYWORD)

## AIM:
To Create a Java program to implement super keyword in constructor.

## ALGORITHM :
1.  Start the Program.
2.	Define class `College`:
-	a) Define method `display()` that prints "I am a Vehicle"
3.	Define class `Student` that extends `College`:
-	a) Override method `display()` to print "I am a Car"
-	b) Define method `print()`:
-	i) Call `super.display()` to invoke `display()` from `College` class
-	ii) Call `this.display()` to invoke `display()` from `Student` class
4.	Define `Main` class with `main` method:
-	a) Create a `Student` object `sc`
-	b) Call `sc.print()` to execute the `print()` method
5.	End







## PROGRAM:
 ```
/*
Program to implement a Constructor Chaining using Java
Developed by: A.DHANUSH
RegisterNumber: 212222220010
*/
```

## Sourcecode.java:

```

class Gadgets {

  //Write Your code Here
  void display()
  {
      System.out.println("I am a Gadget");
  }
}

class Parrot extends Gadgets {

//Write Your code Here  
void display()
{
    System.out.println("I am a Laptop");
}
void print()
{
    super.display();
}
  
}

public class Main {
  public static void main(String[] args) {
      
      //Write Your code Here
      Parrot obj=new Parrot();
      obj.display();
      obj.print();
  }
}

```





## OUTPUT:

![image](https://github.com/user-attachments/assets/240c300f-e074-4f6e-ba85-ca586e2ca81c)


## RESULT:
Thus the java program for constructor chaining was executed successfully.




