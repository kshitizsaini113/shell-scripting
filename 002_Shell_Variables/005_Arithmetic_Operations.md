# Arithmetic Operations

> [USER INPUT](004_User_Input.md) --- [HOME](../README.md) --- [CHECKING VARIABLE EXISTANCE](006_Checking_variable_existance.md)

Arithmetic operations in BASH is done by,
```
$ (( EXPRESSION ))
```

|||
|-------------|-------------|
|+ -> Addition|echo $(( 20+5 ))|
|- -> Subtraction|echo $(( 20-5 ))|
|* -> Multiplication|echo $(( 20*5 ))|
|/ -> Divison|echo $(( 20/5 ))|

## Order of precedence

|||
|-------------|-------------|
|++,--|Post increment/decrement|
|++,--|Pre increment/decrement|
|+,-|Uranary plus/minus|
|!,~|Logical, Bitwise negation|
|**|Exponential|
|*,/,%|Multiplu, Devide, Remainder|
|+,-|Addition, Subtraction|
|<<,>>|Left/Right bitwise shift|
|<=,>=,<,>|Comparisons|
|==,!=|Equality, inequality|
|&|Bitwise AND|
|^|Bitwise XOR|
|!|Bitwise OR|
|&&|Logical AND|
|\|\||Logical OR|
|? :|Conditional|
|=|Assignment|
|,|Comma|