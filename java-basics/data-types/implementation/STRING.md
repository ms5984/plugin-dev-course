# `String (Java Implementation)`
The String data type holds a sequence of 0 or more Unicode characters. 

In Java, Strings do not have a primitive type, only a class: `String`.

#### When we write Strings directly in code, we use double-quotes: `""`.
An example for the phrase, `Hello, World`: "Hello, World".
##### This syntax is called a String literal.
Notice how the period comes after the closing double-quote. Every Java String literal begins
and ends with a double-quote character; if you want to include punctuation it must come before
the closing quote--"inside" the pair.
##### But I need to write a String that contains double-quotes!
You can use <kbd>Backslash</kbd> to form an escape sequence: `\"`. Typing this will tell the
computer to ignore the usual function of double-quotes (to open/close literals), allowing
the literal to continue and for you to include the double-quote:
###### Literal: `"\"The rain in Spain stays mainly in the plain!\" he repeated."`
###### Contents of the String: `"The rain in Spain stays mainly in the plain!" he repeated.`
##### I need to write multiple lines!
There's a character for that™, and it has its own escape sequence too! `\n`.
###### Literal: `"This is one line.\nThis is another."`
###### Contents of String:
```
This is one line.
This is another.
```

### Usage
This data type is used to store text or any character.

### Size
The in-memory size of a String is difficult to determine and will vary from runtime to runtime.
However, we can approximate String sizes with some information and calculations:

> A String actually uses two objects: the String object, and a char array.
> * The characters that make up the String are stored as an array.
> * The String object in Java 8 is approximately 28 bytes (224 bits).
> * The array itself uses 16 bytes (128 bits) while each character adds an extra 2 bytes (16 bits).

##### If we imagine the String object associated with this literal: "Hello":
* The String contains 5 characters, so we have `5 * 16 = 80 bits (10 bytes) total` used to store all chars.
* We then have 128 bits (8 bytes) for the char array itself: `80 + 128 = 208 bits (26 bytes)`.
* Finally, we have the size of the String object itself, which is `224 bits (28 bytes)`.
* In total, the size of the String `Hello` would come to `208 + 224 = 432 bits (54 bytes)`.

### Example
```java
String a = "Hello world!";
String b = "This is a string.";
```
