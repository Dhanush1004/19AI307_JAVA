![image](https://github.com/user-attachments/assets/63f0aa91-b199-45ed-bca0-ca65fe28ed0f)# Ex.No:2(D) MULTI-DIMENSIONAL ARRAY

## AIM:
To create a java program that returns the sum of all the values in a 2D array.

## ALGORITHM :
1.	Start the program.
2.	Import `Scanner` and define class `sum`
3.	In `main`:
-	a) Create `Scanner` object `sc`
-	b) Read `rows` and `cols` from user
-	c) Declare 2D array `arr[rows][cols]`
4.	Populate `arr` using nested loops with user input
5.	Initialize `sum` to `0`
6.	Calculate the sum of all elements in `arr` using nested loops
7.	Print "The sum of all values in the 2D array is: " + `sum`
8.	End



## PROGRAM:
 ```
/*
Program to implement a Multi Dimensional Array using Java
Developed by: A.DHANUSH
RegisterNumber:  212222220010
*/
```

## Sourcecode.java:
```
public class Main
{
    public static void sum(int[][] arr)
    {
        int sum = 0;
        for(int i = 0; i < arr.length; i++)
        {
            for(int j = 0; j < arr[0].length; j++)
            {
                sum = sum + arr[i][j];
            }
        }
        System.out.print("Sum of all elements is: " + sum);
    }
    public static void main(String[] args)
    {
        int[][] arr = {
                {1, 2, 3, 4, 5},
                {2, 4, 6, 8, 10},
                {1, 3, 5, 7, 9}
        };
        sum(arr);
    }
}
```

## OUTPUT:

![image](https://github.com/user-attachments/assets/127777a7-eba3-451d-847e-6a11bb8360e0)


## RESULT:
Thus the java program that returns the sum of all the values in a 2D array was executed successfully.


