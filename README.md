AIM:To study and implement Operators in C++
THEORY:
Operators are integral to programming in C++. They allow manipulation of data, execution of computations, and decision-making through expressions. Understanding operators is essential for writing efficient and effective C++ programs.

1. Definition and Purpose
Operators in C++ are symbols that tell the compiler to perform specific mathematical, logical, or relational operations on one or more operands (variables or values). They form the building blocks of expressions and influence how data is processed.

2. Types of Operators
C++ supports various categories of operators:

Arithmetic Operators: Perform basic mathematical operations.

+ (Addition)

- (Subtraction)

* (Multiplication)

/ (Division)

% (Modulus for remainder)

Relational Operators: Compare two values and return a boolean result.

== (Equal to)

!= (Not equal to)

< (Less than)

> (Greater than)

<= (Less than or equal to)

>= (Greater than or equal to)

Logical Operators: Combine multiple conditions.

&& (Logical AND)

|| (Logical OR)

! (Logical NOT)

Bitwise Operators: Manipulate bits within integral types.

& (AND)

| (OR)

^ (XOR)

~ (NOT)

<< (Left shift)

>> (Right shift)

Assignment Operators: Assign values to variables.

=, +=, -=, *=, /=, %= etc.

Increment and Decrement Operators: Modify values by 1.

++ (Increment)

-- (Decrement)

Conditional (Ternary) Operator: Short form of if-else.

?:

Other Operators: sizeof, typeid, pointer operators (*, &), and more.

3. Operator Precedence and Associativity
Operators have precedence levels that dictate the order in which parts of an expression are evaluated. For example, multiplication has higher precedence than addition, so in 3 + 4 * 5, multiplication happens first.

Associativity determines the order of evaluation when operators of the same precedence appear together. Most operators are left-associative (evaluated left to right), but some, like assignment, are right-associative.

Understanding these rules is essential to avoid logical errors and unexpected results.

4. Unary, Binary, and Ternary Operators
Unary operators operate on a single operand, e.g., ++x, -y.

Binary operators operate on two operands, e.g., x + y.

Ternary operator takes three operands: condition ? expr1 : expr2.

5. Operator Overloading
C++ supports operator overloading, allowing programmers to redefine the behavior of operators for user-defined data types (classes and structs). This improves code readability and allows objects to be manipulated using intuitive syntax.
