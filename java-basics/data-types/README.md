# `2.1 Data types`
### What is a data type?
A data type is a way to classify data to the computer.
It indicates how the program plans to use that data, e.g.
* in the form of a number for performing maths
* as letters in a word
* as the on/off state of a program feature

The main data types are:
  - String ([See more](fundamentals/STRING.md))
  - Integer ([See more](fundamentals/INTEGER.md))
  - Floating-point ([See more](fundamentals/FLOATING_POINT.md))
  - Character ([See more](fundamentals/CHARACTER.md))
  - Boolean ([See more](fundamentals/BOOLEAN.md))


### Data types in Java
Java offers a versatile approach to these main data types.
Appropriate variations of the numeric types are provided for different data applications.
These data types are implemented as a mix of both so-called "primitive" and non-primitive types.

Java's 8 primitive data types:
  - boolean ([See more](implementation/BOOLEAN.md))
  - char ([See more](implementation/CHAR.md))
  - byte ([See more](implementation/BYTE.md))
  - short ([See more](implementation/SHORT.md))
  - int ([See more](implementation/INT.md))
  - long ([See more](implementation/LONG.md))
  - float ([See more](implementation/FLOAT.md))
  - double ([See more](implementation/DOUBLE.md))

Java's non-primitive data types are infinite; really, they are mostly classes that we refer to as data types.
You will use many provided by the Java library, such as `String`, but later you can make your own to store,
manipulate and manage data. All Java primitives have an associated non-primitive wrapper class: these are used
wherever an Object is required (like with Lists or Maps). Frequently, wrapper classes will also contain static
utility methods that can help you to convert data or perform other common stateless operations.

5 basic non-primitive Java data types:
  - Class ([See more](implementation/CLASS.md))
  - Object ([See more](implementation/CLASS.md#what-is-an-object))
  - Array ([See more](implementation/ARRAY.md))
  - String ([See more](implementation/STRING.md))
  - Interface ([See more](implementation/INTERFACE.md))
