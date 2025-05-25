# Ex.No:8(B) IO-FILE READER/WRITER
## AIM:
To create a java program to append a string in a file “testout.txt” using Writer.

## ALGORITHM :
1.	It creates a file testout.txt, writes "Welcome to Java File Concept -Reader" to it, and displays this initial content.
2.	It reopens the file in append mode and adds "Hi Everybody" at the end of the existing content.
3.	It reads the file's content (Welcome to Java File Concept -Reader1234567890) and displays it.
4.	The file is deleted using file.delete().
5.	It tries to read the file again, but this throws an exception since the file no longer exists.

## PROGRAM:
 ```
/*
Program to implement a IO File Reader/Writer using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
Writer w1 = new FileWriter("testout.txt",true);  
w1.append("Hi Everybody");  
w1.close();  
System.out.println("Append the character in the File Successfully");  
```
## OUTPUT:

![image](https://github.com/user-attachments/assets/2b8d9885-79ca-4ae7-9af3-fc89ad666c26)

## RESULT:
Thus, the java program to append a NUMBER in a file “testout.txt” using Writer.was executed and verified successfully


