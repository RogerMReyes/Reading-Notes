# Operators and Loops

JacaScript has both Binary and Unary Operators  

Binary example - operand1 operator operand2  
x * y

Unary example - operator operand  
x++ or x--

## Assignment Operators

- The assignment operator assigns a value to its left operand based on the value of its right operand  
- Assignments also have shorthand that can also be used
- When chaining expression the assignment expressions are grouped right to left and influenced by parentheses
- Avoid putting a variable chain in `const`, `let`, and `var` statements as it often does not work

Assignment | x = f() | x = f()  
Addition assignment | x += f() | x = x + f()  
Subtraction assignment | x -= f() | x = x - f()  
Multiplication assignment | x \*= f() | x = x \* f()  
Division assignment | x /= f() | x = x / f()  
Remainder assignment | x %= f() | x = x % f()  
Exponentiation assignment | x \**= f() | x = x ** f()  
Left shift assignment | x <<= f() | x = x << f()  
Right shift assignment | x >>= f() | x = x >> f()  
Unsigned right shift assignment | x >>>= f() | x = x >>> f()  
Bitwise AND assignment | x &= f() | x = x & f()  
Bitwise XOR assignment | x ^= f() | x = x ^ f()  
Bitwise OR assignment | x |= f() | x = x | f()  
Logical AND assignment | x &&= f() | x && (x = f())  
Logical OR assignment | x ||= f() | x || (x = f())  
Logical nullish assignment | x ??= f() | x ?? (x = f())

## Comparison Operators

- Compares its operands and returns a logical value depending on whether the camparison is true

Equal (==) | Returns true if the operands are equal.  
Not equal (!=) | Returns true if the operands are not equal.  
Strict equal (===) | Returns true if the operands are equal and of the same type. See also Object.is and sameness in JS.  
Strict not equal (!==) | Returns true if the operands are of the same type but not equal, or are of different type.  
Greater than (>) | Returns true if the left operand is greater than the right operand.  
Greater than or equal (>=) | Returns true if the left operand is greater than or equal to the right operand.  
Less than (<) | Returns true if the left operand is less than the right operand.  
Less than or equal (<=) | Returns true if the left operand is less than or equal to the right operand.

## `for` Statements

- Start out with an initial expression
- the condition expression will evaluate if it is true which determines if the loop continues
- the increment expression will execute if present and repeat the loop process
- Example - for(let i = 0; i < 5; i++) the initial variable i is equal to 0 and since the condition is true since 0 is less than 5 the code following will execute. Once all the code is executed i will be incrementally increased by 1 and the condition expression will be checked again

## `while` Statements

- Will execute code until a specified condition evaluates to false 
- Example - for(x < y) the code following this for loop will repeatedly execute if x is less than y since the expression is true and will break only when x is greater than y which makes the expression false

[Return to the Main Page](https://rogermreyes.github.io/reading-notes/)