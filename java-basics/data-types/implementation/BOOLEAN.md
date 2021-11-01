# `Boolean (Java Implementation)`
The Boolean data type can store only two possible values: `true` and `false`.
#### In Java, booleans have a primitive type: `boolean`, and a wrapper class: `Boolean`.
This is how Booleans are represented in Java:
```java
class BooleanFundamentals {
    void example() {
        // We use the `boolean` datatype to declare a Boolean variable
        boolean aTrueBoolean = true; // We use the `true` literal for true/1/"on" values
        boolean aFalseBoolean = false; // We use the `false` literal for false/0/"off" values
        System.out.println(aTrueBoolean);
        System.out.println("Not true, but " + aFalseBoolean);
    }
}
```

As with many other simple data types, a String can technically hold a Boolean value;
running `BooleanFundamentals#example` should show us the String `true` printed to
standard out--followed by `Not true, but false`.

Let's look at the latter expression:
```java
class BooleanFundamentals {
    void example2() {
        boolean aFalseBoolean = false;
        String output = "Not true, but " + aFalseBoolean;
        System.out.println(output);
    }
}
```
The expression `"Not true, but " + aFalseBoolean` will be evaluated as
`"Not true, but " + String.valueOf(aFalseBoolean)`. The return type of `String#valueOf(boolean)` is always a string;
therefore the computer has treated our Boolean as a String.

### Usage
This data type is used for simple true/false conditions.

### Size
Booleans only specify 1 bit of information and thus are 1 bit in size in the best case.

### Example
```java
boolean a = false;
boolean b = true;
```
