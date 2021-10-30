# `Interface (Java Implementation)`
An Interface is a reference type in Java, which makes it similar to a [Class](./CLASS.md).
Like a Class, an interface contains methods--however, these methods are implicitly abstract.
Classes can `implement` an interface, and by doing so that class inherits the methods of the interface.

Along with abstract methods, an interface can contain default methods, static methods and nested types.
Method bodies exist only for default and static methods. (Requires Java 8 and above.)

The main difference in the use of interfaces and classes is that while a class describes the behaviours
**and** attributes of an object, an interface describes only the behaviours. You may also hear this
described as an object's `contract`.

### What can you do with an interface?
  - You **cannot** instantiate an interface.
  - An interface cannot contain constructors.
  - Methods in an interface are considered implicitly `public abstract`.
  - An interface is not `extended` by a class--it is `implemented`.
  - An interface can extend multiple interfaces; a class can extend multiple interfaces.

### Example of an interface, Car
```java
public interface Car {

    void setThrottle(int throttle);

}
```
