# Ex.No:5(B) TIGHTLY ENCAPSULATED CLASS

## AIM:
To Create a java program to display the reverse string and  use tightly encapsulated class.
## ALGORITHM :

1. Start the program and import Scanner for user input.

2. Create a StringReverser class with:

   A private String variable text.
   
   A method setText to store user input.

   A method getReversedText that uses StringBuilder to reverse and return the text.

3. In the Main class, create:

   A Scanner object to read user input.
   
   A StringReverser object to process the input.

4. Read a string input from the user, set it using setText, and print the reversed text using getReversedText.

5. Close the Scanner and end the program.
## PROGRAM:
 ```
/*
Program to implement a tightly encapsulated class using Java
Developed by: A.DHANUSH
RegisterNumber: 2122222220010
*/
```

## Sourcecode.java:


```
import java.util.Scanner;

class StringReverser {
    private String text;

    public void setText(String text) {
        this.text = text;
    }

    public String getReversedText() {
        StringBuilder sb = new StringBuilder(text);
        return sb.reverse().toString();
    }
}

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        StringReverser sr = new StringReverser();

        String input = scanner.nextLine();
        sr.setText(input);

        System.out.println(sr.getReversedText());
        scanner.close();
    }
}
```




## OUTPUT:

```
Input     Expected    Got

pot       top         top

lap       pal         pal

```

## RESULT:
Thus a java program to display the reverse string and  use tightly encapsulated classwas executed successfully.



