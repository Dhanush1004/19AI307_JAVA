# Ex.No:11(B)   JAVA MAP & HASHMAP AND HASHTABLE
## AIM :
To Create a java program to retrieve the key and value from hashtable for all input value.

## ALGORITHM :

1.	Start
2.	Import `java.util.*`
3.	Define class `A` with `main` method:
-	a) Initialize `Scanner` and read integer `n`
-	b) Create a `Hashtable` named `hash` to store integer keys and string values
4.	Use a loop to:
-	a) Read an integer and string from the user
-	b) Add the integer as the key and the string as the value in `hash`
5.	Use an enhanced `for` loop to iterate through `hash` and print each key-value pair
6.	End




## PROGRAM:
 ```
/*
Program to implement a JAVA MAP & HASHMAP AND HASHTABLE using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:

```
import java.util.*;  
public class Mapp{  
 public static void main(String args[]){ 
     
  HashMap<Integer,String> map=new HashMap<>(); 
  Scanner sc=new Scanner(System.in);
  
  int size=sc.nextInt();
  for(int i=0;i<size;i++)
  {
  Integer a=sc.nextInt();
  String b=sc.next();
  map.put(a,b);  
  } 
 
  
 Iterator<Integer> keySetIterator = map.keySet().iterator(); while(keySetIterator.hasNext()){ Integer key = keySetIterator.next(); System.out.println("key: " + key + " value: " + map.get(key)); }

System.out.println("Size of Map: " + map.size()); map.clear(); 
System.out.println("Size of Map: " + map.size()); 

 }  
}
```

## OUTPUT:

```
Input	                      Expected	                       Got	
2                       key: 100 value: sri           key: 100 value: sri
100                     key: 101 value: krishna       key: 101 value: krishna
sri                     Size of Map: 2                Size of Map: 2
101                     Size of Map: 0                Size of Map: 0
krishna


```


## RESULT:
Thus the java program to retrieve the key and value from hashtable for all input value was executed successfully.







