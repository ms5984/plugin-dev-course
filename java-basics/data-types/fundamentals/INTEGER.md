# `Integer (Fundamentals)`
### What is an Integer?
An Integer is a signed, whole number.
They can be negative or positive (the "signed" part), but cannot contain a decimal value (the "whole" part).

#### Examples:
* 73
* 182
* -6

### Integers have a finite range.
This fact leads us to describe briefly the two most common implementations of Integer:
* "int32" or int - uses 32 bits to describe a signed integer (31+1 for the sign)
* "int64" or long - uses 64 bits to describe a signed integer (63+1 for the sign)

Further, there are two other common types that can also be considered implementations of Integer:
* byte or "int8" - uses 8 bits to describe a signed integer (7+1 for the sign)
* "int16" or short - uses 16 bits to describe a signed integer (15+1 for the sign)

See how integers are implemented in Java:
* [here](../implementation/INT.md) (for int32)
* [here](../implementation/LONG.md) (for int64).
* [here](../implementation/BYTE.md) (for byte).
* [here](../implementation/SHORT.md) (for int16).
