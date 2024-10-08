# Java Data Types and For Loop Examples

This repository contains examples of Java programs demonstrating basic data type declarations, user input handling, and the use of `for` loops. The code and documentation are written in English.

## Examples

### 1. Data Type Example

This program demonstrates the declaration of various native data types in Java and how to read user input for each type. The following data types are covered:
- byte
- short
- int
- long
- float
- double
- char
- boolean
- String

#### Code

```java
import java.util.Scanner;

public class DataTypeExample {
    public static void main(String[] args) {
        // Initialize Scanner object to read input from the console
        Scanner scanner = new Scanner(System.in);

        // Declare variables for each primitive data type
        byte byteValue;
        short shortValue;
        int intValue;
        long longValue;
        float floatValue;
        double doubleValue;
        char charValue;
        boolean booleanValue;
        
        // Declare a String variable
        String stringValue;

        // Prompt and read a byte value
        System.out.print("Please enter a byte value: ");
        byteValue = scanner.nextByte();
        System.out.println("The byte value entered is: " + byteValue);

        // Prompt and read a short value
        System.out.print("Please enter a short value: ");
        shortValue = scanner.nextShort();
        System.out.println("The short value entered is: " + shortValue);

        // Prompt and read an int value
        System.out.print("Please enter an int value: ");
        intValue = scanner.nextInt();
        System.out.println("The int value entered is: " + intValue);

        // Prompt and read a long value
        System.out.print("Please enter a long value: ");
        longValue = scanner.nextLong();
        System.out.println("The long value entered is: " + longValue);

        // Prompt and read a float value
        System.out.print("Please enter a float value: ");
        floatValue = scanner.nextFloat();
        System.out.println("The float value entered is: " + floatValue);

        // Prompt and read a double value
        System.out.print("Please enter a double value: ");
        doubleValue = scanner.nextDouble();
        System.out.println("The double value entered is: " + doubleValue);

        // Prompt and read a char value
        System.out.print("Please enter a char value: ");
        charValue = scanner.next().charAt(0);
        System.out.println("The char value entered is: " + charValue);

        // Prompt and read a boolean value
        System.out.print("Please enter a boolean value (true/false): ");
        booleanValue = scanner.nextBoolean();
        System.out.println("The boolean value entered is: " + booleanValue);

        // Prompt and read a String value
        System.out.print("Please enter a string value: ");
        stringValue = scanner.next();
        System.out.println("The string value entered is: " + stringValue);

        // Close the scanner to avoid resource leaks
        scanner.close();
    }
}
```

### 2. Using For Loop to Iterate Over a Range

This example demonstrates the use of a for loop in Java to iterate over a sequence of numbers.

### Code Explanation
The program:

1. Initializes a variable max that defines the upper limit of the loop.
2. Uses two different for loops to iterate from 0 to max - 1.
3. Prints the value of i on each iteration.

#### Code

```java
public class ForLoopExample {
    public static void main(String[] args) {
        int max = 10; // Define the maximum number of iterations

        // First for loop - incrementing i by 1 until i is equal to max
        for (int i = 0; i < max; i++) {
            System.out.println("First loop iteration: " + i);
        }

        // Second for loop - similar structure but demonstrates redundancy
        for (int i = 0; i < max; i++) {
            System.out.println("Second loop iteration: " + i);
        }
    }
}
````

### Repository and Documentation

Both of these solutions have been uploaded to a GitHub repository. The repository includes:

README.md file with detailed documentation explaining the purpose of each program and instructions for running the code.
Properly commented code following best practices for clarity and understanding.
You can find the repository here:

[GitHub Repository: Java Data Types and For Loop Examples]: (https://github.com/NireysBarras/Java-Data-Types-and-For-Loop-Examples/blob/main/README.md)
