# Ex.No:10(C)             JAVA LIST INTERFACE
 ## AIM :

To Create a List interface implemented by arraylist class, adding n elements to object of List interface , insert new string in index position 1 ,update the elements at index 2 and print all the elements inside the List interface object before and after update the element.


## ALGORITHM :
1.	Start
2.	Import `java.util.*`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` and an empty `ArrayList` named `list`
-	b) Read integer `n`
4.	Check if `list` is empty, print corresponding message
5.	Use a loop to add `n` strings to `list`
6.	Check if `list` is empty again, if no print the output
7.	End

## PROGRAM:
 ```
/*
Program to implement a JAVA LIST INTERFACE using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:

```
import java.util.*;


public class GFG {

	public static void main(String args[])
	{
		Scanner sc=new Scanner(System.in);
		List<String> al = new ArrayList<>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++)
        {
				al.add(sc.next());
        }
        System.out.println(al);
        al.add(1,sc.next());
		
		System.out.println("After add element in index 1 :" + al);
		al.set(2,sc.next());
		System.out.println("After update:" + al);
	}
}
```


## OUTPUT:


![image](https://github.com/user-attachments/assets/904aa933-07c1-406e-a3f0-2b23c6e92342)


## RESULT:
Thus the java program implemented a List interface for array list was executed and verified successfully.










