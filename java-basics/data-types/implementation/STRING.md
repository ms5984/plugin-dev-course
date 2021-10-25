# `String (Java Implementation)`
The string data type is 0 or more Unicode characters. 

In Java, strings don't have a primtive type, only the wrapper class `String`.

### Usage
This data type is used to store strings of text, and any character.

### Size
The size of a string is hard to determine, and will vary version to version. However, we can approximate String sizes from some information we can calculate.

A String object actually creates two objects, one being the String object you'd expect, and the other being a char array. The letters that make up your string are actually just an array of characters in Java. The String object in Java 8 is approximately 28 bytes (224 bits). The character array (without the characters in) is 16 bytes (128 bits), then for every character you add it's an extra 2 bytes (16 bits).

So if we had the string "Hello", it contains 5 characters, so we have 5 * 16 bits for the char size, which is 80 bits (10 bytes). Then we have 128 bits (8 bytes) for the char array itself, which in total is 208 bits (38.5 bytes). And finally the size of the String object itself, which is 224 bits (28 bytes). So in total the size of our string "Hello" would come to 432 bits or 54 bytes.

### Example
```java
String a = "Hello world!"
String b = "This is a string."
```
