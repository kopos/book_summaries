Pattern
-------
- pattern name
- problem
- solution
- consequences

Operation
---------
                               
    +-------+       +--------+    
    |request+-------> object |    
    +-------+       +-+----^-+    
                      |    |      
                      |    |      
                      |    |      
                   +--v----+---+  
                   | operation |  
                   +-----------+

Defined by a signature comprised of
- name
- parameters
- return value

Class vs Type
-------------
Class: How the object is *implemented*
Type: How the object behaves i.e Set of requests to which the object can *respond*
      **An object can have many types**

So an object has both Interface (type) inheritance as well as Implementation (class) inheritance.
Interface inheritance is also called **subtyping**


Design Patterns
---------------
Can be classified by purpose and by scope

By Purpose
==========
- Creational patterns
- Structural patterns
- Behavioral patterns

By scope
========
- Class
- Object

List
====
Abstract Factory
Adapter
Bridge
Builder
Chain of Responsibility
Command
Composite
Decorator
Facade
Factory Method
Fly weight
Iterator
Mediator
Memento
Observer
Prototype
Proxy
Singleton
Strategy
Template Method
Visitor
