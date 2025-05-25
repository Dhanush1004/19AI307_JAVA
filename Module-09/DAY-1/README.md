# Ex.No:9(A)          DATA I/O STREAM
## AIM:
To write data to multiple files using ByteArrayOutputStream, demonstrating the ability to write the same data to multiple output streams.
## ALGORITHM :

1. Create two `FileOutputStream` objects (`out` and `out2`) to write to `F1.txt` and `F2.txt`.
2. Create a `ByteArrayOutputStream` (`str`) to temporarily hold data in memory.
3. Use `write()` to write a byte (in this case, the value `69`, corresponding to the letter 'E') to the `ByteArrayOutputStream`.
4. Use `writeTo()` method of `ByteArrayOutputStream` to write the data from memory to both `FileOutputStream` objects (`out` and `out2`).
5. Close the `ByteArrayOutputStream` once the data is written to the files, then print `"Success..."` to indicate the operation completed.

## PROGRAM:
 ```
/*
Program to implement a DATA I/O STREAM using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010

FileOutputStream out = new FileOutputStream("F1.txt");
FileOutputStream out2 = new FileOutputStream("F2.txt");
ByteArrayOutputStream str = new ByteArrayOutputStream();
str.write(69);
str.writeTo(out);
str.writeTo(out2);
str.close();
System.out.println("Success...");
*/
```


## OUTPUT:

![Screenshot 2025-05-10 063658](https://github.com/user-attachments/assets/500d48b9-8986-48cf-ba59-745105a93f15)


## RESULT:
Thus the Java Program To write data to multiple files using ByteArrayOutputStream, demonstrating the ability to write the same data to multiple output streams executed successfully.

