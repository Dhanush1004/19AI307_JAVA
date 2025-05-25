# Ex.No:12(D) JAVA QUEUE
## AIM:
To Write a java program to display the added elements from the Priority Queue.


## ALGORITHM :
1.	Start the Program
2.	Import `PriorityQueue` and `Scanner`
3.	Define class `Main` with `main` method:
-	a) Initialize `Scanner` to read input
-	b) Create a `PriorityQueue` of integers
4.	Read integer `n` from user input for the number of elements
5.	Use a loop to:
-	a) Read integers and add them to the `PriorityQueue`
6.	Check if the `PriorityQueue` is not empty:
-	a) Remove and display the highest-priority element using `poll()`
7.	Display the remaining elements in the `PriorityQueue`
8.	End.





## PROGRAM:
 ```
/*
Program to implement a JAVA QUEUE using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.*;

public class PriorityQueueDemo {
	

	public static void main(String args[])
	{
	
		PriorityQueue<Integer> pQueue = new PriorityQueue<Integer>();
        
	    Scanner sc=new Scanner(System.in);
	    int size=sc.nextInt();
	    for(int i=0;i<size;i++){
	        pQueue.add(sc.nextInt());
	    }
	   Iterator iterator = pQueue.iterator();
	   System.out.println("Iterate the elements from the queue using while loop:");
  
        while (iterator.hasNext()) {
            System.out.print(iterator.next() + " ");
        }
		
	}
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/4f22db10-f5f0-4e7a-a4c7-8dda4f3e8fa2)


## RESULT:
Thus the java program to display the added elements from the Priority Queue is executed successfully.


