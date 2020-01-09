# Design Patterns

Design patterns are elegant solutions to repeating problems in software development.

A design pattern shows you how to structure objects in your system and how those objects should talk to each other. These patterns were made famous by Erich Gamma, Richard Helm, Ralph Johnson, and John Vlissides (also known as Gang Of Four) in their 1994 book *Design Patterns: Elements of Reusable Object-Oriented Software*[1]. One of the main benefits of using design pattens is to help programmers communication with other programmers at a higher, more abstract level.

Warning: Inappropriate use of patterns may unnecessarily increase complexity.[2]


The GOF patterns include 23 design patterns in three categories: Creational, Structural, & Behavioral.

---

## Creational
Creational design patterns describe different ways to create objects.

#### Abstract Factory:
- Provides an interface for creating families of related or dependent objects without specifying their concrete classes.

#### Builder:
- Separate the construction of a complex object from its representation, allowing the same construction process to create various representations.

#### Factory Method:
- Define an interface for creating a single object, but let subclasses decide which class to instantiate. 
- Lets a class defer instantiation to subclasses.

#### Prototype:
- Specify the kinds of objects to create using a prototypical instance, and create new objects from the 'skeleton' of an existing object, thus boosting performance and keeping memory footprints to a minimum.

#### Singleton:
- Ensure a class has only one instance, and provide a global point of access to it.

---

## Structural
Structural design patterns describe the relationships between different objects.

#### Adapter, Wrapper, or Translator:
- Convert the interface of a class into another interface clients expect.
- Lets classes work together that could not otherwise because of incompatible interfaces.

#### Bridge:
- Decouple an abstraction from its implementation allowing the two to vary independently.

#### Composite:
- Compose objects into tree structures to represent part-whole hierarchies.
- Lets clients treat individual objects and compositions of objects uniformly.

#### Decorator:
- Attach additional responsibilities to an object dynamically keeping the same interface.
- Provide a flexible alternative to subclassing for extending functionality.

#### Facade:
- Provide a unified interface to a set of interfaces in a subsystem.
- Defines a higher-level interface that makes the subsystem easier to use.

#### Flyweight:
- Use sharing to support large numbers of similar objects efficiently.

#### Proxy:
- Provide a surrogate or placeholder for another object to control access to it.

---

## Behavioral
Behavioral design patterns describe common communication patterns among objects.

#### Chain of Responsibility:
- Avoid coupling the sender of a request to its receiver by giving more than one object a chance to handle the request.
- Chain the receiving objects and pass the request along the chain until an object handles it.

#### Command:
- Encapsulate a request as an object, thereby allowing for the parameterization of clients with different requests, and the queuing or logging of requests.
- Allows for the support of undoable operations.	

#### Interpreter:
- Given a language, define a representation for its grammar along with an interpreter that uses the representation to interpret sentences in the language.

#### Iterator:
- Provide a way to access the elements of an aggregate object sequentially without exposing its underlying representation.

#### Mediator:
- Define an object that encapsulates how a set of objects interact.
- Promotes loose coupling by keeping objects from referring to each other explicitly, and it allows their interaction to vary independently.

#### Memento:
- Without violating encapsulation, capture and externalize an object's internal state allowing the object to be restored to this state later.

#### Observer, or Publish/Subscribe:
- Define a one-to-many dependency between objects where a state change in one object results in all its dependents being notified and updated automatically.

#### State:
- Allow an object to alter its behavior when its internal state changes. The object will appear to change its class.

#### Strategy:
- Define a family of algorithms, encapsulate each one, and make them interchangeable.
- Lets the algorithm vary independently from clients that use it.

#### Template Method:
- Define the skeleton of an algorithm in an operation, deferring some steps to subclasses.
- Lets subclasses redefine certain steps of an algorithm without changing the algorithm's structure.

#### Visitor:
- Represent an operation to be performed on the elements of an object structure.
- Lets a new operation be defined without changing the classes of the elements on which it operates.

---

### Relevant Sources
1. [Design Patterns Elements of Reusable Object-Oriented Software][1] by Gang Of Four (Gamma, Helm, Johnson, & Vlissides)
2. [Code Complete: A Practical Handbook of Software Construction, 2nd Edition.][2] by Steve McConnell

[1]:https://www.amazon.com/Design-Patterns-Object-Oriented-Addison-Wesley-Professional-ebook/dp/B000SEIBB8
[2]:https://www.amazon.com/Code-Complete-Practical-Handbook-Construction/dp/0735619670/
