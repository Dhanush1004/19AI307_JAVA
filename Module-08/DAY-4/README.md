# Ex.No:8(D) BUFFER INPUT/OUTPUT STREAM

## AIM:
 To create a java program file for displaying the data from the file using FileOutputStream & BufferedOutputStream.

## ALGORITHM :
1.	Import java.io.* and java.util.* for file handling and user input.
2.	Create a file named sample.txt and write "This is a line of text inside the file." using FileWriter.
3.	Close the FileWriter to save the content to sample.txt.
4.	Open sample.txt with a FileOutputStream wrapped in a BufferedOutputStream for efficient reading.
5.	Prompt the user to enter the number of bytes to skip using Scanner.
6.	Skip the specified number of bytes in the file and print the remaining content.
7.	Close the BufferedOutputStream and FileOutputStream to release system resources.

## PROGRAM:
 ```
/*
Program to implement a Buffer Input/Output Stream using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:
```
       
           FileOutputStream fout=new FileOutputStream("sample.txt");    
     BufferedOutputStream bout=new BufferedOutputStream(fout);  
     Scanner sc=new Scanner(System.in);
     String s=sc.nextLine();    
     byte b[]=s.getBytes();    
     bout.write(b);    
    
     bout.close();    
     fout.close();    
       
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/861176ee-7103-449d-978b-d2c3fe47d729)


## RESULT:
Thus, the java program file for displaying the data from the file using FileInputStream & BufferedInputStream was executed and done successfully.

