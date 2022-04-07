
  
  
  
# SOFTWARE DESIGN PATTERNS  
  
In software engineering, a design pattern is a general repeatable solution to a commonly occurring problem in software design. These solutions were obtained by trial and error by numerous software developers over quite a substantial period of time.  
In Short: Design patterns are solutions to general problems that software developers faced during software development.  
  
> In 1994, four authors Erich Gamma, Richard Helm, Ralph Johnson and  
> John Vlissides published a book titled "Design Patterns - Elements of  
> Reusable Object-Oriented Software" which initiated the concept of  
> Design Pattern in Software development. These authors are collectively  
> known as Gang of Four (GOF).  
  
**Types of Design Patterns**  
  
1. Creational Patterns  
2. Structural Patterns  
3. Behavioral Patterns  
  
  
## CREATIONAL DESIGN PATTERNS :  
  
Creational design patterns provide various object creation mechanisms, which increase flexibility and reuse of existing code.  
  
**1)Factory Method**  
Provides an interface for creating objects in a superclass, but allows subclasses to alter the type of objects that will be created.  
  
**2)Abstract Factory**  
Let's you produce families of related objects without specifying their concrete classes.  
Abstract Factory patterns work around a super-factory which creates other factories. This factory is also called a factory of factories.  
  
**3)Builder**  
Let's you construct complex objects step by step. The pattern allows you to produce different types and representations of an object using the same construction code.  
  
**4)Prototype**  
Let's you copy existing objects without making your code dependent on their classes.  
  
**5)Singleton**  
The Singleton pattern is one of the simplest design patterns. This type of design pattern comes under creational pattern as this pattern provides one of the best ways to create an object.  
  This pattern involves a single class which is responsible to create an object while making sure that only a single object gets created. This class provides a way to access its only object which can be accessed directly without the need to instantiate the object of the class.  
  
  
## STRUCTURAL DESIGN PATTERNS:  
  
Structural design patterns explain how to assemble objects and classes into larger structures while keeping these structures flexible and efficient.  
  
  
**1)Adapter**  
Adapter pattern works as a bridge between two incompatible interfaces. This pattern combines the capability of two independent interfaces.  
  
**2)Decorator**  
Decorator pattern allows a user to add new functionality to an existing object without altering its structure. This pattern acts as a wrapper to the existing class.  
  
**3)Facade**  
Facade pattern hides the complexities of the system and provides an interface to the client using which the client can access the system. This pattern adds an interface to an existing system to hide its complexities.  
  
  
## BEHAVIORAL DESIGN PATTERNS:  
  
These design patterns are all about Class's objects communication. Behavioral patterns are those patterns that are most specifically concerned with communication between objects.  
  
**1)Strategy**  
Strategy is a behavioral design pattern that lets you define a family of algorithms, put each of them into a separate class, and make their objects interchangeable.  
  
**2)Repository**  
A repository represents an architectural layer that handles communication between the application and data source.  
  
> **Note:** I have mentioned only commonly used design patterns, all design patterns are not covered here.
