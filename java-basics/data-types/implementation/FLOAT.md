# `Float (Java Implementation)`
The Float data type is a single-precision IEEE-754 floating-point number.
Its value range is unlimited.

In Java:
* Floats have a primitive type: `float`, and a wrapper class: `Float`.
* Use the `float` primitive type to declare variables.
* Use the `Float` wrapper class for its utility methods or when working with generics like Lists or Maps.
* We write Floats as a normal decimal followed by the letter F: `2.0f`.
  - **This syntax is called a floating-point (float) literal.**
  - The F is not case-sensitive, but traditionally it is lowercase.

### Usage
This data type can be used over a [Double](./DOUBLE.md) to save memory in large arrays of floating-point numbers
and to improve computation speed by sacrificing precision.

##### The Float data type should never be used for base-10 decimal values like currency.
**It is unsuitable for arithmetic where Base-10 accuracy is important.**
`0.1` expressed as a Float does not equal `0.1` as a decimal (or `10^-1`);
this precision issue compounds with further calculation.

### Size
A Float is 4 bytes (32 bits) in size.

### Example
```java
float a = 3462.5f;
float b = -89347.921875F;
```
