# `String (Fundamentals)`
### What is a String?
A String is simply a group 0 or more characters (letters, numbers or symbols).
It can contain any character that exists within the computing world--both ASCII and Unicode,
as the latter is effectively a superset of ASCII.
###### ASCII what?
Both ASCII and Unicode are what are called character encodings. Each character is given a unique numerical
(binary) representation which computers use when storing that character. Unicode (a later and much richer
encoding) simply carries forward the representations established by ASCII, and as such is backwards-compatible
accepting simpler ASCII-only data.

#### An example of a String is `Hello, world!`.
The length of this String is 13 (10 letters, 1 space and 2 symbols).

#### We can have Strings made of numbers because they're also characters, e.g. `34`.
Bear in mind that when working with such a String that the computer will only know to treat it
as a String--and not necessarily as the number `34`.

See how Strings are implemented in Java [here](../implementation/STRING.md).
