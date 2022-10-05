The *numeric types* are the integral types and the floating-point types.

The *integral types* are *byte,short,int, and long*, whose values are 8-bit, 16-bit, 32-bit and 64-bit signed two's-complement integers.
*char* are 16-bit unsigned integers representing UTF-16 code units.

The *floating-point types* are float, whose values include the 32-bit IEEE 754 floating-point numbers, and *double* values include the 64-bit IEEE 754 floating-point numbers.

The *boolean* type has exactly two values: true and false.

| name | size | range | sample |
| ----- | ----- | ----- | ----|
| boolean | 1 bit |  |  false , true|
| unsigned integers char | 16 bits = 2 Bytes| \u0000 ~ \uffff ( 0 ~ 65535 ) |  | 
|byte | 8 bits = 1 Byte |-128 ~ 127 |
| short|  16 bits = 2 Bytes | -32768 ~ 32767 |
|int | 32 bits = 4 bytes | -2,147,483,648 ~ 2,147,483,647  | |
|long | 64 bits = 8 bytes | -923372036854775808 ~ 923372036854775807 | |
| float|32 bits | | |
|double|64 bits | | |

A *literal* is the source code representation of a value of a primitice type, the *String* type, or the *null* type.

An *integer* literal may be expressed in decimal (base 10), hexadecimal (base 16), octal (base 8), or binary (base 2). 

An integer literal is of type *long* if it is suffixed with an ASCII letter L or l; otherwise it is of type int

A floating-point literal is of type *float* if it is suffixed with an ASCII letter F or f; otherwise its type is *double* and it can optionally be suffixed with an ASCII letter D or d.

#The _char_ type
the 16 bit _char_ type is insufficient to describe all Unicode characters.

# Integer type
## All integer types are SIGNED

# Floating-Point type
_double_ refers to the fact that these numbers have twice the precision of the _float_ type

A variable name must begin with a lettter and must be a sequence of letters or digits.

| conversions without information loss | source | target |
| ------ |----- | ----- |
| | byte | short |
| | short | int| 
| | char| int| 
| | int | long|
| | int | double| 
| | float | double|

| conversions lose precision| source  | target |
| ---- | ---- | ----- |
| | int | float| 
| | long | float| 
| |long | double|

# Operator
when two values are combined with a binary operator, both operands are converted to a common type before the operation is carried out
 * If either of the operands is of type _double_ , the other one will be converted to a _double_
 * Otherwise, if either of the operands is of type _float_, the other one will be converted to a _float_
 * Otherwise, if either of the operands is of type _long_, the other one will be converted to a _long_
 * Otherwise, both operands will be converted to an int


If an interger addition overflows, then the result is the low-order bits of the mathematical sum as represented in some
sufficiently large two's-complement format. If overflow occurs, then the sign of the result is not the same as the sign of the 
mathematical sum of the two operand values.

