# `Random Number Generation`
Generating random numbers in Java is pretty simple, and can be done in several ways.

Note that "random" number generation in Java is actually what is referred to as pseudorandom, because like anything in programming, there is an algorithm behind the generation of the numbers - making them not truly random.

### Method 1
#### Using `Math.random()`
One of the easiest ways to generate a random number is by using the Math library within Java. We can make use of `Math.floor()` to round down, and inside of that use our `Math.random()`, in the format of the formula below.
```java
Math.floor(Math.random() * (max - min + 1) + min);
```
This allows us to generate a random number in the range of our minimum and maximum values (inclusive).

Example:
```java
int max = 100;
int min = 20;
int randomNumber = Math.floor(Math.random() * (max - min + 1) + min);

System.out.println("Your random number is: " + randomNumber);
------------
OUTPUT
Your random number is: 56
```

### Method 2
#### Using `ThreadLocalRandom`
Another very easy way to generate random numbers is using the `ThreadLocalRandom` class. You may know about the `Random` class, and know that both of these methods actually use `Random`, so why shouldn't you just use `Random` yourself? If you're opting towards Method 1, then there is not really any reason to not use `Random` yourself, however Method 2 is the safest and most efficient way to generate random numnbers in Java.

`ThreadLocalRandom` is a class in Java that makes use of the `Random` class to generate a random number. The reason it is better and more efficient than using `Random` is because it is stored and accessed only on one thread. Using `Random` wherever you want to means more allocations of memory, potential concurrency issues, and a few other things - using `ThreadLocalRandom` solves all of this for you.

`ThreadLocalRandom` is a singleton by design, meaning there is only ever one instance of it. You can obtain the instance of it by doing `ThreadLocalRandom.current()` - this just returns the instance of `Random` that is stored within the class. From here you can do everything you would normally do with a `Random` object, because it is exactly that.

The methods you will mostly want to use from this are `nextInt()`, `nextDouble()`, and maybe `nextBoolean()`. These methods are pretty self explanatory, but you can find examples of each below.

Example:
```java
int randomInt = ThreadLocalRandom.current().nextInt(0, 10);
double randomDouble = ThreadLocalRandom.current().nextDouble();
boolean randomBoolean = ThreadLocalRandom.current().nextBoolean():

System.out.println("Random Integer: " + randomInt);
System.out.println("Random Double: " + randomDouble);
System.out.println("Random Boolean: " + randomBoolean);
------------
OUTPUT
Random Integer: 7
Random Double: 0.23
Random Boolean: false
```
