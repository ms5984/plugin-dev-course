# `Short/Int16 (Java Implementation)`
The `short` data type can store values ranging between -32,768 (-2^16) and 32,767 (2^16 - 1) (inclusive).

In Java:
* Int16s have a primitive type: `short`, and a wrapper class: `Short`.
* We write numbers that fall within the `short` range as they are (without thousands separator or decimal point): `10`.
##### This syntax is called an integer literal.
Though you may not include thousands separators (such as commas/full stops),
you may use underscores in place of separators if desired for clarity: `30_000`.
They will simply be ignored by the compiler.
#### It is a compile-time error to set a `short` variable to a value outside its possible range.

### Usage
This data type is used to save memory in large arrays: it achieves this because a `short` is 2 times smaller
than an `int` in Java. Assuming your [Integer](../fundamentals/INTEGER.md)'s values need not exceed the
bounds of a `short`, this type can be used in place of an `int`.

### Size
A short is 2 bytes (16 bits) in size.

### Example
```java
short a = 23457;
short b = -4572;
// short b = -457243; // This is a compile-time error; value is outside the range of short
```
