# `Byte/Int8 (Java Implementation)`
The `byte` data type can store values ranging between -128 (-2^7) and 127 (2^7 - 1) (inclusive).

In Java:
* Bytes have a primitive type: `byte`, and a wrapper class: `Byte`.
* We write numbers that fall within the `byte` range as they are (without thousands separator or decimal point): `10`.
##### This syntax is called an integer literal.
#### It is a compile-time error to set a `byte` variable to a value outside its possible range.

### Usage
This data type is used to save memory in large arrays: it achieves this because a `byte` is 4 times smaller
than an `int` in Java. Assuming your [Integer](../fundamentals/INTEGER.md)'s values need not exceed the
bounds of a `byte`, this type can be used in place of an `int`.

### Size
A byte, funnily enough, is 1 byte (8 bits) in size.

### Example
```java
byte a = 7;
byte b = -13;
// byte b = 128; // This is a compile-time error; 128 is outside the range of byte
```
