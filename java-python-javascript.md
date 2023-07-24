---
description: Pass by value vs Pass by reference
---

# Java / Python / JavaScript

Java / Java Script&#x20;

Primitive Type => Pass by value (for java, primitive use stack memory)

Non - primitive Type => Pass by value (reference address of the objects, in java the object is stored in heap)

Python&#x20;

All arguments are passed by object reference&#x20;

Even int, float, String etc are object&#x20;

Immutable objects (int, float, String, tuple) => behave like java primitive type

* a reference to the int object with value (1) is passed
* but if the reference is redefined to hold other value (2) - the original object of value (1) is not changed

Mutable objects (object, list etc) => behave like java non-primitive type



Reference&#x20;

* [https://www.digitalocean.com/community/tutorials/java-heap-space-vs-stack-memory](https://www.digitalocean.com/community/tutorials/java-heap-space-vs-stack-memory)
* [https://www.geeksforgeeks.org/g-fact-31-java-is-strictly-pass-by-value/](https://www.geeksforgeeks.org/g-fact-31-java-is-strictly-pass-by-value/)
* [https://www.geeksforgeeks.org/is-python-call-by-reference-or-call-by-value/](https://www.geeksforgeeks.org/is-python-call-by-reference-or-call-by-value/)
