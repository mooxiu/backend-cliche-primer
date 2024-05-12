# Programming Language

## Data Structures

## Others

### Garbage Collection

### String in Java
`String` objects in Java are immutable.
- [Why Java Strings are Immutable](https://www.geeksforgeeks.org/java-string-is-immutable-what-exactly-is-the-meaning/#:~:text=The%20String%20is%20immutable%2C%20so,a%20single%20%E2%80%9CString%20instance%E2%80%9D.)

#### String pool
> the special memory region where Strings are stored by the JVM

> Thanks to the immutability of Strings in Java, the JVM can optimize the amount of memory allocated for them by storing only one copy of each literal String in the pool. 

> When we create a String variable and assign a value to it, the JVM searches the pool for a String of equal value. If found, the Java compiler will simply return a reference to its memory address, without allocating additional memory. 

- [Guide to Java String Pool](https://www.baeldung.com/java-string-pool)

