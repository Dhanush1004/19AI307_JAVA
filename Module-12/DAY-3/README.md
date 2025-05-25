# Ex.No:12(C)             JAVA STACK & VECTOR
 ## AIM :

To Write a java program to create vector and read the elements for two vector in java collection.(Use equals method )
## ALGORITHM :

1.	Start the Program
2.	In `main`:
-	a) Create a `Scanner` object to read input.
-	b) Read an integer `n1` (the size of the first vector).
-	c) Initialize `Vector<String> vector1`.
-	d) Use a `for` loop to read `n1` strings and add each to `vector1`.
3.	Repeat similar steps for a second vector:
a)	Read an integer `n2` (size of the second vector).
b)	Initialize `Vector<String> vector2`.
c)	Use a `for` loop to read `n2` strings and add each to `vector2`.
4.	Use `equals()` to compare `vector1` and `vector2` and print whether they are equal.
5.	End.



## PROGRAM:
 ```
/*
Program to implement a JAVA STACK & VECTOR  using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.*;
public class VectorDemo {
	public static void main(String args[])
	{
		Vector<String> vec_tor1 = new Vector<String>();
        Scanner sc=new Scanner(System.in);
        int size=sc.nextInt();
	    for(int i=0;i<size;i++)
	    {
		vec_tor1.add(sc.next());
	    }
	   	System.out.println("The vector is: " + vec_tor1);

	    Vector<String> vec_tor2 = new Vector<String>();
        int size2=sc.nextInt();
        for(int i=0;i<size2;i++)
        {
        vec_tor2.add(sc.next());
        }
       
  
       System.out.println("The Vector is: "
                           + vec_tor2);
  
        System.out.println("Are both of them equal? "
                           + vec_tor1.equals(vec_tor2));
		}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/9735e21e-602b-4252-8f94-995cc3508352)

## RESULT:

Thus the java program to create vector and read the elements for two vector in java collection.(Use equals method ) was executed successfully.








