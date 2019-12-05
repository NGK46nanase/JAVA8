| name | size | range | sample |
| ----- | ----- | ----- | ----|
| boolean | 1 bit |  |  false , true|
| unsigned integers char | 16 bits = 2 Bytes| |  | 
|byte | 8 bits = 1 Byte | |
| short|  16 bits = 2 Bytes | |
|int | 32 bits = 4 bytes | | |
|long | 64 bits = 8 bytes | | |
| float|32 bits | | |
|double|64 bits | | |

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
