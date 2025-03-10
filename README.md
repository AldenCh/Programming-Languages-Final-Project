**All files run assume you have a functional environment**

This programming language was developed using ANTLR grammar definition and a Kotlin backend.
An example of all the syntax and functionality provided in this language is given in **worksheet.ipynb**

**BEFORE YOU RUN MAKE SURE YOU RUN THE MAKEFILE**

**This programming language supports**
1. Variable declaration with String, Numeric, Binary and Boolean data types
   - String variable: **b = "string"**
   - Numeric variable: **a = 0**
   - Binary variable: **0b101** for 5
   - Boolean variable: **c = true** or **c = false**
3. Arithmetic operations
   - Addition: **+**
   - Subtraction: **-**
   - Multiplication: **\***
   - Division: **/**
4. String operations
   - String multiplication: **"test" * 2** will return **"testtest"**
   - String concatenation: **"My name is " ++ "Alden"** will return **"My name is Alden**
5. Loops
   - For loop: **for(i in 1..2) {}**
   - While loop: **while (a > 0) {}**
6. Functions
   - Built in print function: **print("Hello World")**
   - Function definition: **function(var1, var2){}**
7. Logical Operations
   - Logical NOT: **!true** or **!false**
   - Logical AND: **true && false**
   - Logical OR: **true || false**
   - Logical XOR: **true ^^ false**
8. Bitwise Operations (Functional for binary and numeric variables)
   - Assuming **a = 5** and **b = 9**
   - Bitwise AND: **a & b** is **1**
   - Bitwise OR: **a | b** is **13**
   - Bitwise XOR: **a ^ b** is **12**
   - Bitwise NOT: **~a** is 250
   - Bitwise shift left 1: **b << 1** is 18
   - Bitwise shift right 1: ** b >> 1** is 4
