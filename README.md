## Python Design Patterns

Software design patterns are general reusable solutions to problems which occur
over and over again in object-oriented design enviroment. It is not a finished 
design that can be transformed into source code directly, but it is template how
to solve the problem. We can classify them by purpose into creational (abstract 
the instantiation process), structure (how classes and objects are composed to form 
larger structures) and behavioral patterns (the assignment of responsibilities between 
objects).  

#### Creational Patterns
Creational patterns provides essential information regarding the Class instantiation or the object instantiation. Class Creational Pattern and the Object Creational pattern is the major categorization of the Creational Design Patterns. While class-creation patterns use inheritance effectively in the instantiation process, object-creation patterns use delegation effectively to get the job done.
- [Abstract Factory], families of product objects
- [Builder], how a composite object gets created
- [Factory Method], subclass of object that is instantiated
- [Prototype], class of object that is instantiated
- [Singleton], the sole instance of a class 
#### Structural Patterns
Structural design patterns are about organizing different classes and objects to form larger structures and provide new functionality while keeping these structures flexible and efficient. Mostly they use Inheritance to compose all the interfaces. It also identifies the relationships which led to the simplification of the structure.
- [Adapter], interface to an object
- [Bridge], implementation of an object 
- [Composite], structure and composition of an object
- [Decorator], responsibilities of an object without subclassing
- [Façade], interface to a subsystem
- [Flyweight], storage costs of objects
- [Proxy], how an object is accessed (its location)
#### Behavioral Patterns
Behavioral patterns are all about identifying the common communication patterns between objects and realize these patterns. These patterns are concerned with algorithms and the assignment of responsibilities between objects.
- [Chain of Responsibility], object that can fulfill a request
- [Command], when and how a request is fulfilled
- [Interpreter], grammar and interpretation of a language
- [Iterator], how an aggregate's elements are accessed
- [Mediator], how and which objects interact with each other
- [Memento], what private information is stored outside an object, and when 
- [Observer], how the dependent objects stay up to date
- [State], states of an object
- [Strategy], an algorithm
- [Template Method], steps of an algorithm
- [Visitor], operations that can be applied to objects without changing their classes

### Other Languages
In my repository you can find implementation of desgin patterns also in languages as 

* [Design Patterns in C++]
* [Design Patterns in Java]
* [Design Patterns in Python]

### References
Design patterns in this repository are based on

* [Design Patterns by The "Gang of Four"]
* [Head First: Design Patterns]
* [Wikipedia]

[Design Patterns in C++]: https://github.com/JakubVojvoda/design-patterns-cpp
[Design Patterns in Java]: https://github.com/JakubVojvoda/design-patterns-java
[Design Patterns in Python]: https://github.com/JakubVojvoda/design-patterns-python

[Design Patterns by The "Gang of Four"]: https://en.wikipedia.org/wiki/Design_Patterns
[Head First: Design Patterns]: http://www.headfirstlabs.com/books/hfdp/ 
[Wikipedia]: https://en.wikipedia.org/wiki/Software_design_pattern

[Abstract Factory]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/abstract-factory
[Builder]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/builder
[Factory Method]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/factory-method
[Prototype]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/prototype
[Singleton]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/singleton
[Adapter]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/adapter
[Bridge]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/bridge 
[Composite]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/composite
[Decorator]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/decorator
[Façade]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/facade
[Flyweight]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/flyweight
[Proxy]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/proxy
[Chain of Responsibility]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/chain-of-responsibility
[Command]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/command
[Interpreter]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/interpreter
[Iterator]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/iterator
[Mediator]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/mediator
[Memento]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/memento
[Observer]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/observer
[State]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/state
[Strategy]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/strategy
[Template Method]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/template-method
[Visitor]: https://github.com/JakubVojvoda/design-patterns-python/tree/master/visitor
