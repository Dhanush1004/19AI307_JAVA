# Ex.No:5(D) IS-A RELATIONSHIP AND HAS-A RELATIONSHIP
## AIM:
   To Create a java program create a three class and apply is-a relationship concepts and display the output refer sample test.
 
## ALGORITHM :

1. Start the program.

2. Create a class Animal with a method eat() that prints "I can eat".

3. Create a class Person that inherits from Animal, and add a method name() that prints "My name is Rohu".

4. Create a Main class that inherits from Person:

   In the main method:
      
      Create an object of Main.
      
      Call name() to print the name.
      
      Call eat() to print the eating ability.

5. End the program.

## PROGRAM:
 ```
/*
Program to implement a IS-A RELATIONSHIP AND HAS-A RELATIONSHIP using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
class Animal {
    public void eat() {
        System.out.println("I can eat");
    }
}

class Person extends Animal {
    public void name() {
        System.out.println("My name is Rohu");
    }
}

public class Main extends Person {
    public static void main(String[] args) {
        Main obj = new Main();
        obj.name();
        obj.eat();
    }
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/1846d70a-097b-4b4d-a830-f0f1da459732)


## RESULT:
Thus the java program to find factorial of number using class and object concepts and apply the has-a relationship was executed successfully.
