# `Char (Java Implementation)`
The char data type is a single Unicode character.
Its range of values spans from `\u0000` (or 0) and `\uFFFF` (or 65,535) (inclusive)(`2^16-1`).

In Java:
* [Characters](../fundamentals/CHARACTER.md) have a primitive type: `char`, and a wrapper class: `Character`.
* We write characters as a single character surrounded by apostrophes (`'a'`).
##### This syntax is called a character literal.
Other examples of Java character literals:
* `C`
* ` `
* `e`
* `{`
* `3`

#### Number initialization
Sometimes you will see a `char` initialized with a number rather than a literal, like this:
```java
class CharacterFundamentals {
    void example() {
        char c = 42; // ASCII for the asterisk
    }
}
```
This form may occur (especially in a loop); refer to a
[table like this](https://www.rapidtables.com/code/text/unicode-characters.html) to decode the resulting character.

### Usage
This data type is used to store singular characters.

### Size
A double is 2 bytes (16 bits) in size.

### Example
```java
char a = 'C';
char b = '{';
```
