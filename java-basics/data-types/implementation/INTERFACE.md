# `Interface (Java Implementation)`
An interface is a reference type in Java, it is similar to a class. Like a class, an interface contains methods - however these methods are abstract. A class can implement an interface, and by doing so that class inherits the abstract methods of the interface.

As well as abstract methods, an interface can also contain default methods, static methods and nested types. Method bodies exist only for default and static methods.

The difference between the uses of interfaces and classes is that, a class describes the attributes and behaviours of an object. Whereas an interface contains the behaviours that a class implements.

### What can't you do with an interface?
  - You cannot instantiate an interface
  - An interface doesn't contain constructors
  - All of the methods in an interface are abstract
  - An interface is not extended by a class, it is implemented
  - An interface can extend multiple interfaces
