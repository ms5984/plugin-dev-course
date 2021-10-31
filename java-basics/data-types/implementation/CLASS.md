# `Class (Java Implementation)`
When starting out, Classes in Java can be hard to wrap your head around--to understand what purpose they serve.
#### An easy way to think about classes is as a template or blueprint for making and using objects.

### What is an object?
A Java object is an instance (defined below) of a Java class. Each object has an identity, a behaviour and a state.

- The state of an object is stored in its fields (defined below).
- The methods (defined below) display and manage the object's behaviour.

Objects are created at runtime from classes. You can create an object using the `new` keyword.

#### Definitions
##### Instance
If a class is only a blueprint, then you can think of an instance as a construction of that blueprint.
The construction will contain everything that the blueprint outlined, but any modifications of the construction
afterward will only apply to that construction and not every other construction of the blueprint.

You can think of it like housing developments; let's say we know we want every third house we build to have 3 bedrooms.
We can make a class that specifies this. However, later on one of the homeowners decides to remodel and turn one of
their three bedrooms into a home office. Now one of the houses only has two bedrooms! The houses started out with
similar structure, but now that one has been changed has **not** meant all the rest have changed as well.

**The construction will contain everything that the blueprint outlined (the fields and methods), but any modifications
made at runtime will only apply to that construction (the instance) and not the blueprint itself (the class).**

##### Field
A field is much like a normal variable, but it belongs to a class--that's all.

##### Method
A method is much like a static method--it's a normal subroutine, but it belongs to a class.

<sub>Some of this is taken from Brandon's explanation of OOP (Object Oriented Programming), if you wish to read further please see [#oop](https://discord.com/channels/397526357191557121/823606772581400638) in the [Plugin Dev Course](https://discord.gg/bsB2Zf2E48) Discord</sub>
