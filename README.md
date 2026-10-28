# COS102---Programming-I

## Week 1: Introduction to Programming and Problem-Solving

### Practical Exercise
Created and executed my first Java programme.

### File
- week01/FirstProgram.java

### How to Run
```
cd week01
javac FirstProgram.java
java FirstProgram
```

## Week 2: Development Environment and First Java Program

### Objective
To configure the Java development environment, write a simple Java program, compile it, execute it and submit the source code through GitHub.

### Tools Used
- Java Development Kit (JDK)
- Visual Studio Code
- Git
- GitHub

### Files
- `week02/HelloWorld.java`: First Java program using `println()`.
- `week02/PrintExample.java`: Shows the difference between `print()` and `println()`.
- `week02/ErrorExample.java`: Corrected version of the "find and fix the error" exercise (missing semicolon).

### How to Run
1. Open a terminal in the `week02` directory.
2. Compile the program using `javac HelloWorld.java`.
3. Run the program using `java HelloWorld`.

## Week 3: Variables, Data Types, Expressions and Input/Output

### Objectives
- Declare and initialize Java variables.
- Use appropriate primitive and reference data types.
- Perform arithmetic calculations.
- Read keyboard input using Scanner.
- Display formatted output.
- Compile, test and submit Java programs using GitHub.

### Programs
1. `week03/SimpleCalculator.java`
   - Performs arithmetic calculations on two numbers.
2. `week03/AverageCalculator.java`
   - Calculates the total and average of three scores.
3. `week03/ItemCost.java`
   - Calculates the total cost using quantity and unit price.

### How to Run
Open a terminal in the `week03` directory.

Compile and run the calculator:
- `javac SimpleCalculator.java`
- `java SimpleCalculator`

Compile and run the average calculator:
- `javac AverageCalculator.java`
- `java AverageCalculator`

Compile and run the item-cost program:
- `javac ItemCost.java`
- `java ItemCost`

### Testing
| Program | Input | Expected output |
|---|---|---|
| SimpleCalculator | 20, 4 | Sum 24.00, Difference 16.00, Product 80.00, Quotient 5.00 |
| SimpleCalculator | 5, 0 | Division is undefined for a zero divisor. |
| AverageCalculator | Amina Bello, 70, 80, 90 | Total 240.00, Average 80.00 |
| ItemCost | Exercise book, 3, 1500 | Total cost 4500.00 |
