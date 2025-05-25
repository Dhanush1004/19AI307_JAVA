# Ex.No:10(E)  JAVA LINKEDHASH SET

## AIM:
To Write a Java program to extract a portion of a list. index value from 1 to 3.

## ALGORITHM :
```
  1)Start
  2)Create a Scanner object to read input from the user.
  3)Create an empty ArrayList of type String named list_Strings.
  4)Read an integer input size from the user.
  (This represents the number of elements to be added to the list.)
  5)Repeat the following steps size times (using a for loop):
  6)Read a string input from the user.
  7)Add the string to the list_Strings.
  8)Print the original list using System.out.println().
  9)Create a sublist sub_List from list_Strings using:
  10)list_Strings.subList(1, 3)
  (This extracts elements from index 1 to 2 — index 3 is not included.)
  11)Print the sublist using System.out.println().
  12)End

```

## PROGRAM:
 ```
/*
Program to implement a LINKEDHASH SET
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
import java.util.*;
public class Ex {
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        List<String> list_Strings = new ArrayList<String>();
        int size=sc.nextInt();
        for(int i=0;i<size;i++){
            list_Strings.add(sc.next());
        }
        System.out.println("Original list: " + list_Strings);
        List<String> sub_List = list_Strings.subList(1, 3);
        System.out.println("Index of 1 to 3 elements print: " + sub_List);
    }
}
```



## OUTPUT:

![image](https://github.com/user-attachments/assets/5b1348a4-c224-4b03-bdcc-0243e11ea1de)


## RESULT:

Thus the java program was successfully uses LinkedHashSet to store and display elements while maintaining insertion order and ensuring uniqueness. It also shows the correct count of unique elements. 
