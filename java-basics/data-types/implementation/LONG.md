# `Long/Int64 (Java Implementation)`
The `long` data type can store values ranging between -9,223,372,036,854,775,808 (-2^63) and 9,223,372,036,854,775,807 (2^63 - 1) (inclusive).

In Java:
* Int64s have a primitive type: `long`, and a wrapper class: `Long`.
* We write numbers that fall within the `long` range as they are (without thousands separator or decimal point),
followed by a trailing L: `10L`.
##### This syntax is called an integer (long) literal.
Though you may not include thousands separators (such as commas/full stops),
you may use underscores in place of separators if desired for clarity: `30_000_000L`.
They will simply be ignored by the compiler.

### Usage
This data type is used when you require numbers of large size and precise value.

### Size
A long is 8 bytes (64 bits) in size.

### Example
```java
long a = 926593485L
long b = -62354727689L
```
