# Ex.No:12(E)  JAVA DEQUEUE

## AIM:
To demonstrate how to remove and display the first element from a Deque using the pollFirst() method in Java Collections with String values.
## ALGORITHM :

1.	Import java.util.*.
2.	Create a Deque using LinkedList.
3.	Add several string elements to the deque.
4.	Use pollFirst() to remove and return the first element.
5.	Print the removed element.
6.	Display the remaining elements in the deque.

## PROGRAM:
 ```
/*
Program to implement a JAVA DEQUEUE
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.*;

public class deQueueDemo {
	

	public static void main(String args[])
	{
	
		Deque<Integer> dq = new LinkedList<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        dq.add(sc.nextInt());
	    }
	    System.out.println("Display the element of Dequeue:");
		System.out.println(dq);
        System.out.println("Display the element of Dequeue after add first element :");
        dq.addLast(150);
		System.out.println(dq);
		
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/1e62a533-9914-4388-a0d2-85efe9f57251)

## RESULT:

Thus the java program successfully demonstrates how to use pollFirst() to remove and display the first element from a Deque of strings.


