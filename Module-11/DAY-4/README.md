# Ex.No:11(D) RELATED TO MAP CONCEPTS

## AIM:
To Create a java program for map interface concept and follow the below conditions and display the value and string.(use comparingByValue() ).

## ALGORITHM :
```
1. Start the program and create a Scanner to take input from the user.

2. Create an empty HashMap<Integer, String> called map.

3. Read an integer size and then use a loop to input key-value pairs into the map.

4. Convert the map to a stream of entries and sort by value using Map.Entry.comparingByValue().

5. Use forEach to print the sorted map entries.

```

## PROGRAM:
 ```
/*
Program to implement a RELATED TO MAP CONCEPTS using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:

```
import java.util.*;  
public class MapExample3{  
 public static void main(String args[]){  
Map<Integer,String> map=new HashMap<Integer,String>();          
      Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  }   

      map.entrySet()  
       
      .stream()  
   
      .sorted(Map.Entry.comparingByValue()) 

      .forEach(System.out::println);  
 }  
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/5fa1d1c3-42e0-4faf-b37e-85685f72acaa)


## RESULT:
Thus the java program to insert and display the key and values using map interface was  executed and verified successfully.


