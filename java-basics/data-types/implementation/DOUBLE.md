# `Double (Java Implementation)`
The Double data type is a double-precision IEEE-754 floating-point number.
Its value range is unlimited; [precision is not](https://www.exploringbinary.com/floating-point-converter/).

In Java:
* Doubles have a primitive type: `double`, and a wrapper class: `Double`.
* Use the `double` primitive type to declare variables.
* Use the `Double` wrapper class for its utility methods or when working with generics like Lists or Maps.
* We can write Doubles as a normal decimal plainly: `2.0`.
* We can also write Doubles as a normal decimal followed by the letter D: `2.0d`.
##### This syntax is called a floating-point (double) literal.
The D is not case-sensitive, but traditionally it is lowercase.

### Usage
This data type is generally used for larger decimal values where memory usage and speed
of calculations are not as valuable as their precision.

##### The Double data type should never be used for base-10 decimal values like currency.
**It is unsuitable for arithmetic where Base-10 accuracy is important.**
`0.1` expressed as a Double does not equal `0.1` as a decimal (or `10^-1`);
this precision issue compounds with further calculation.

### Size
A Double is 8 bytes (64 bits) in size.

### Example
```java
double a = 873245317283142.125;
double b = -23463854.625d;
```
