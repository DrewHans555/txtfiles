# SOLID Principles

SOLID is a mnemonic acronym for five design principles intended to make software designs more understandable, flexible, and maintainable. The theory of SOLID principles was first introduced by Robert Martin in his 2000 paper *Design Principles and Design Patterns*.

## Concepts
#### Single Responsibility Principles:
- A class should have one, and only one, reason to change.

#### Open-Closed Principle:
- Software entities should be open for extension, but closed for modification.

#### Liskov Substitution Principle:
- Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.
- Any implementation of an abstraction should be substitutable in any place that the abstraction is accepted.

#### Interface Segregation Principle:
- Many client-specific interfaces are better than one general-purpose interface.
- A client should not be forced to implement an interface that it doesn't use.

#### Dependency Inversion Principle:
- One should depend upon abstractions, not concretions.
- High-level modules should not depend on low-level modules. Both should depend on abstractions.
- Abstractions should not depend on details. Details should depend on abstractions.

### Relevant Sources
1. Agile Software Development, Principles, Patterns, and Practices by Robert C. Martin
