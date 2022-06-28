# Backend Interview Cliché Primer

> 小生を面接、首実検の後、不採用という恥辱はご容赦願いたし
> (山崎豊子『不毛地帯』)

According to my tech interview experiences, the coding part and system design part is not that difficult for me. However, I failed mainly in some backend knowledge cliche part (while you can solve coding and system design problems by thinking, you would be freeze if someone ask you about a fancy concpet that you have never heard about). To not fall over in the same place twice, I decide to summarize some knowledges that might be helpful to know.

To make it as simple as possible, this repository should contain only **Backend** part. As there are already a lot of good answers, articles, videos about those questions, I will only do the aggregation job.

This repository is an imitation of [system-design-primer](https://github.com/donnemartin/system-design-primer). Salute to [system-design-primer](https://github.com/donnemartin/system-design-primer).

## Contributions
Feel free to sumibit PR to help:
- Adjust the format, make it easier to read
- Fix errors (including grammar errors)
- Improve or add new sections (remember to re-generate table of content if you add new sections)
- Translation

## Table of Content
  - [Network](#network)
      - [OSI](#osi)
      - [http vs http2](#http-vs-http2)
      - [TCP vs UDP](#tcp-vs-udp)
      - [Layer 4 Load Balancer vs Layer 7 Load Balancer](#layer-4-load-balancer-vs-layer-7-load-balancer)
      - [SNI, ESNI](#sni-esni)
      - [Describe you input an URL until you see the webpage.](#describe-you-input-an-url-until-you-see-the-webpage)
  - [Programming Language](#programming-language)
    - [Garbage Collection](#garbage-collection)
  - [Concurrency](#concurrency)
  - [OOP](#oop)
    - [High Cohension, Low Coupling](#high-cohension-low-coupling)
    - [IOC:](#ioc)
  - [Distributed System](#distributed-system)
    - [CAP theorem](#cap-theorem)
  - [Data Structure](#data-structure)
    - [Implement a HashMap](#implement-a-hashmap)

## Network

---

#### OSI
- [Wikipedia: OSI model](https://en.wikipedia.org/wiki/OSI_model)
- [The OSI Model - Explained by Example](https://www.youtube.com/watch?v=7IS7gigunyI)

#### http vs http2
> HTTP/2 is a replacement for how HTTP is expressed “on the wire.” It is not a ground-up rewrite of the protocol; HTTP methods, status codes and semantics are the same, and it should be possible to use the same APIs as HTTP/1.x (possibly with some small additions) to represent the protocol.

> The focus of the protocol is on performance; specifically, end-user perceived latency, network and server resource usage. One major goal is to allow the use of a single connection from browsers to a Web site.
(https://http2.github.io/)

- [HTTP/2 webpage](https://http2.github.io/)
- [How HTTP/2 Works, Performance, Pros & Cons and More](https://www.youtube.com/watch?v=fVKPrDrEwTI&t=888s)

#### TCP vs UDP
#### Layer 4 Load Balancer vs Layer 7 Load Balancer

---

#### SNI, ESNI
#### Describe you input an URL until you see the webpage.

---

## Programming Language

### Garbage Collection

### String in Java
`String` objects in Java are immutable.
- [Why Java Strings are Immutable](https://www.geeksforgeeks.org/java-string-is-immutable-what-exactly-is-the-meaning/#:~:text=The%20String%20is%20immutable%2C%20so,a%20single%20%E2%80%9CString%20instance%E2%80%9D.)

#### String pool
> the special memory region where Strings are stored by the JVM

> Thanks to the immutability of Strings in Java, the JVM can optimize the amount of memory allocated for them by storing only one copy of each literal String in the pool. 

> When we create a String variable and assign a value to it, the JVM searches the pool for a String of equal value. If found, the Java compiler will simply return a reference to its memory address, without allocating additional memory. 

- [Guide to Java String Pool](https://www.baeldung.com/java-string-pool)


## Concurrency

---

## OOP
### High Cohension, Low Coupling
- [StackOverflow: what does low in coupling and high in cohension mean](https://stackoverflow.com/questions/14000762/what-does-low-in-coupling-and-high-in-cohesion-mean)

### IOC: 
IOC is short for *Inverse Of Control*.
- [Wikipedia: Inversion of Control](https://en.wikipedia.org/wiki/Inversion_of_control)

---

## Distributed System
### CAP theorem

---
## Data Structure
### Implement a HashMap


# Reference
https://github.com/arialdomartini/Back-End-Developer-Interview-Questions
