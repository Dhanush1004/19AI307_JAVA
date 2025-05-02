# Ex.No:3(D) STRING TOKENIZER IN JAVA

## AIM:
To create a java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace.

## ALGORITHM :
1.	Start the Program
2.	Import `Scanner` and `StringTokenizer` and define class `tok`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Initialize the string `str` as "My name is Java Programming"
4.	Create a `StringTokenizer` object `token` to tokenize `str`
5.	Use a `while` loop to iterate through tokens:
-	a) Print each token using `token.nextToken()`
6.	End




## PROGRAM:
 ```
/*
Program to implement a String Tokenizer using Java
Developed by: A.DHANUSH
RegisterNumber:  212222220010
*/
```

## Sourcecode.java:
```
import java.util.*;
public class GFG {
	public static void main(String[] args)
	{
	    Scanner sc=new Scanner(System.in);
		String str = sc.nextLine();
		String[] split = str.split(" ");
		for (int i = 0; i < split.length; i++)
			System.out.println(split[i]);
	}
}
```


## OUTPUT:

![image](https://github.com/user-attachments/assets/75834d6e-4726-4fab-a784-700c00296ddc)


## RESULT:
Thus the java program using StringTokenizer class that tokenizes a string "My name is Java Programming" on the basis of whitespace was executed successfully.
