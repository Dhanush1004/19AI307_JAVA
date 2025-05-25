# Ex.No:6(D) PACKAGES
## AIM:
  To create a Java Program for accessing package from another package using packagename.
 
## ALGORITHM :
1.	Start the Program
2.	Create a directory named pack and save A.java inside it.
2.	Compile A.java from the parent directory using javac pack/A.java.
3.	Create another directory named mypack and save B.java inside it.
4.	Compile B.java from the parent directory using javac mypack/B.java.
5.	Run B from the parent directory with java mypack.B


## PROGRAM:
 ```
/*
Program to implement a Packages using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
package packageone;

public class Message {
    public void showMessage() {
        System.out.println("Hello from packageone!");
    }
}

package packagetwo;

import packageone.Message;  // Import the class from another package

public class PackageTest {
    public static void main(String[] args) {
        Message msg = new Message();  // Create object of class from another package
        msg.showMessage();
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/cf76e54d-27ed-434b-824e-3ba7fb9421e1)


## RESULT:
Thus, the program has accessed the package from another package has been done successfully.
