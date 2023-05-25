# Design-Patterns

## Prerequisites for Learning Design Patterns

<details> 
	<summary> Click Me </summary>
To effectively learn and understand design patterns, it's helpful to have a solid foundation in programming and software development concepts. Here are some recommended prerequisites for learning design patterns:

1. **Object-Oriented Programming (OOP)**: <br> Design patterns are closely tied to object-oriented principles. Familiarize yourself with concepts like classes, objects, inheritance, polymorphism, and encapsulation.
2. **Programming Language**: <br> Choose a programming language you're comfortable with, as most design patterns are language-agnostic and can be implemented in various languages. Understanding the syntax and features of your chosen language will facilitate pattern implementation.
3. **Software Design Principles**: <br> Gain knowledge of fundamental software design principles, such as SOLID principles (Single Responsibility, Open-Closed, Liskov Substitution, Interface Segregation, Dependency Inversion), DRY (Don't Repeat Yourself), and Separation of Concerns. These principles provide a solid foundation for design patterns.
4. **Experience with Real-World Projects**: <br> Having practical experience in developing software applications will help you appreciate the challenges and scenarios where design patterns can be applied. Working on projects with different requirements and complexities enhances your understanding of design patterns' relevance.
5. **Design and Analysis**: <br> Familiarize yourself with design methodologies like UML (Unified Modeling Language) to express design ideas visually. Understanding class diagrams, sequence diagrams, and other UML artifacts helps in effectively communicating and documenting design patterns.
6. **Basic Data Structures and Algorithms**: <br> Some design patterns work in conjunction with data structures and algorithms. Having a basic understanding of data structures (arrays, linked lists, trees, etc.) and algorithms (sorting, searching, graph algorithms, etc.) will be beneficial.
7. **Familiarity with Patterns' Concepts**: <br> Before diving into individual design patterns, grasp the key concepts behind patterns, such as encapsulating variability, separating responsibilities, favoring composition over inheritance, loose coupling, and high cohesion.
8. **Reading and Resources**: <br> Explore books, online tutorials, articles, and resources dedicated to design patterns. Some recommended books include "Design Patterns: Elements of Reusable Object-Oriented Software" by Gamma et al. and "Head First Design Patterns" by Freeman et al.


Remember that learning design patterns is an ongoing process that improves with practice and practical application. Start with simpler patterns and gradually progress to more complex ones. Gain hands-on experience by implementing patterns in your projects to reinforce your understanding.

</details>

## What is and why design pattern in software engineering?

<details>
	<summary> Click Me </summary>
	
A design pattern is a reusable solution to a commonly occurring problem in software design. It provides a structured approach to designing software systems that are flexible, maintainable, and scalable. Design patterns capture best practices and proven solutions developed and refined by experienced software developers over time.

Design patterns are not specific to a particular programming language or technology. They are conceptual templates that can be applied to different situations to solve similar design problems. They promote code reuse, modularity, and maintainability by providing standardized solutions for common design challenges.

Design patterns are categorized into several types, including creational patterns, structural patterns, and behavioral patterns. Creational patterns deal with object creation mechanisms, structural patterns focus on composing objects and classes into larger structures, and behavioral patterns address the interaction and communication between objects.

Some commonly known design patterns include the Singleton pattern, Factory Method pattern, Observer pattern, Decorator pattern, and many more. Each pattern has its specific intent, structure, and implementation details.

By understanding and applying design patterns, software developers can create more robust, flexible, and maintainable software systems. Design patterns are not strict rules or algorithms but rather guidelines that help solve common design problems and promote good software engineering practices.

</details>

**External Resources:**
- [Refactoring Guru: What's a design pattern?](https://refactoring.guru/design-patterns/what-is-pattern)


## The Catalog of Design Patterns

<details>
	<summary> Click Me </summary>
	
We can classify the design patterns like the following catalog:

1. Creational Design Patterns
	- Singleton Pattern
	- Factory Method Pattern
	- Abstract Factory Pattern
	- Builder Pattern
	- Prototype Pattern
	- Object Pool Pattern
2. Structural Patterns:
	- Adapter Pattern
	- Bridge Pattern
	- Composite Pattern
	- Decorator Pattern
	- Facade Pattern
	- Flyweight Pattern
	- Proxy Pattern
3. Behavioral Patterns:
	- Observer Pattern
	- Strategy Pattern
	- Template Method Pattern
	- Command Pattern
	- Iterator Pattern
	- Mediator Pattern
	- State Pattern
	- Visitor Pattern
	- Chain of Responsibility Pattern
	- Interpreter Pattern
	- Memento Pattern
4. Architectural Patterns:
	- Model-View-Controller (MVC) Pattern
	- Model-View-ViewModel (MVVM) Pattern
	- Layered Architecture Pattern
	- Repository Pattern
	- Dependency Injection Pattern
	- Event-Driven Architecture (EDA) Pattern
	- Microservices Pattern
	
It's important to note that this is not an exhaustive list, and there are many other design patterns beyond those mentioned here. Additionally, some patterns may overlap or have variations depending on different sources and interpretations.

Each pattern in the catalog has its own unique purpose and usage, addressing specific design concerns and promoting good software design principles. It's beneficial to understand the different patterns and their application in order to leverage them effectively when designing and developing software systems.

</details>


**External Resources:**
- [Refactoring Guru: The Catalog of Design Patterns](https://refactoring.guru/design-patterns/catalog)

## Before You Proceed

<details>
	<summary> Click Me </summary>

Each design pattern has 3 parts:
1. **Intent:** <br> What does it do?
2. **Problem it solves:** <br> Which problems will we have to face if we don't follow?
3. **Context:** <br> In which situation we have to use this pattern?

Studying a design pattern involves gaining a comprehensive understanding of its concepts, principles, and usage. Here are some steps to effectively study a design pattern:

1. **Read about the Pattern:** <br> Understand the intent, problem it solves, and the context in which it is applicable.
2. **Study the Structure and Participants:** <br> Analyze the structure of the pattern, including the participating classes, their relationships, and responsibilities. Identify the key components and how they interact with each other.
3. **Learn the UML Diagram:** <br> Familiarize yourself with the UML diagram associated with the pattern. Understand the symbols, notations, and relationships depicted in the diagram. It helps visualize the pattern's structure and aids in communication and documentation.
4. **Explore Use Cases:** <br> Study real-world use cases where the design pattern is commonly applied. Understand the scenarios in which the pattern provides benefits and solves specific design problems. This helps you connect the pattern with practical applications.
5. **Review Code Examples:** <br> Look for code examples and implementations of the pattern. Analyze how the pattern is implemented in different programming languages and frameworks. Examine the code structure, class interactions, and the pattern-specific code snippets.
6. **Understand Advantages and Trade-offs:** <br> Gain insights into the advantages and trade-offs of using the pattern. Understand the benefits it provides, such as improved code flexibility, extensibility, or maintainability. Also, be aware of any limitations or potential downsides associated with the pattern.
7. **Implement the Pattern:** <br> Gain hands-on experience by implementing the pattern in your own code. Apply the pattern to solve a problem or improve the design of an existing system. Implementing the pattern in practice solidifies your understanding and helps you identify its practical implications.
8. **Study Related Patterns:** <br> Explore related patterns that are connected or build upon the pattern you are studying. Understand the relationships between patterns and how they complement each other in solving different design challenges.
9. **Review Design Principles:** <br> Relate the design pattern to relevant design principles such as SOLID principles, DRY (Don't Repeat Yourself), and Separation of Concerns. Understand how the pattern aligns with these principles and supports good software design practices.
10. **Practice and Apply:** <br> Continuously practice and apply the pattern in different contexts and projects. As you gain more experience, you'll develop a deeper understanding of the pattern's nuances, variations, and adaptability to different scenarios.

Remember that studying design patterns is an ongoing process. Regularly revisit patterns, review code examples, and explore new use cases to enhance your understanding. By building a solid foundation in design patterns, you'll be better equipped to leverage them effectively in your software development projects.

</details>



## The S.O.L.I.D Principles

<details>
	<summary> Overview </summary>

The **SOLID Principles** are five principles of Object-Oriented class design. They are a set of rules and best practices to follow while designing a class structure.

<figure>
    <img src="https://media.geeksforgeeks.org/wp-content/uploads/20220910005416/SingleResponsibility2.png"
         alt="SOLID Principles">
</figure>

</details>

<details>
	<summary> External Links </summary>

- [Note of Abraar: S.O.L.I.D Principles](https://flying-swordtail-ac1.notion.site/S-O-L-I-D-Principles-0565ab7c568942579a0de7c9e2c19e08)
- [FreeCodeCamp.org: The SOLID Principles of Object-Oriented Programming](https://www.freecodecamp.org/news/solid-principles-explained-in-plain-english/)

</details>

---


Now we will dive into the design patterns one by one. Let's start with **Creational Design Patterns**.

## Creational Design Patterns

<details>
	<summary> Click Me </summary>

Creational design patterns focus on object creation mechanisms, providing solutions to create objects in a flexible and reusable manner. They aim to decouple object creation from the client code, promoting loose coupling and enhancing the maintainability and extensibility of the codebase. 
Here's an introduction to some common creational design patterns:

1. **Singleton Pattern:** <br> The Singleton pattern ensures that only one instance of a class is created and provides a global point of access to it. It is useful when you want to limit the number of instances of a class and ensure that all clients use the same instance.
2. **Factory Method Pattern:** <br> The Factory Method pattern defines an interface for creating objects but allows subclasses to decide which class to instantiate. It provides a way to delegate the object creation to subclasses, promoting extensibility and encapsulating object creation logic.
3. **Abstract Factory Pattern:** <br> The Abstract Factory pattern provides an interface for creating families of related or dependent objects. It allows the creation of object families without specifying their concrete classes. This pattern is useful when you need to create a set of related objects that should be compatible or work together.
4. **Builder Pattern:** <br> The Builder pattern separates the construction of complex objects from their representation, allowing the same construction process to create different representations. It provides a step-by-step approach to building objects, enabling the creation of complex objects with varying configurations.
5. **Prototype Pattern:** <br> The Prototype pattern creates new objects by cloning existing ones, rather than relying on expensive creation mechanisms. It allows you to create new objects by copying existing instances and modifying them as needed. This pattern is useful when the creation of objects is costly or complex.
6. **Object Pool Pattern:** <br> The Object Pool pattern manages a pool of reusable objects, providing efficient object reuse and minimizing the overhead of object creation and destruction. It is beneficial when creating and destroying objects is resource-intensive, and object reuse can significantly improve performance.

These creational design patterns address various object creation scenarios and provide flexible and reusable solutions. Each pattern has its own intent, advantages, and use cases. Understanding these patterns allows you to choose the appropriate approach for object creation in your software projects, promoting code reuse, maintainability, and flexibility.

</details>

### Singleton Pattern - A Creational Design Pattern

<details>
	<summary> Overview </summary>

The Singleton pattern is a creational design pattern that ensures a class has only one instance and provides a global point of access to that instance. It is commonly used when there should be exactly one instance of a class that needs to be shared across multiple parts of the system.

</details>

<details>
	<summary> Intent </summary>

The Singleton pattern ensures that a class has only one instance and provides a way to access it globally.

</details>

<details>
	<summary> Key Components </summary>

1. **Singleton Class:** <br> The class that is designed to have only one instance. It typically provides a static method to access the instance.

</details>

<details>
	<summary> UML Diagram </summary>

<figure>
    <img src="https://refactoring.guru/images/patterns/diagrams/singleton/structure-en-indexed-2x.png"
         alt="UML Diagram, Singleton Pattern">
    <figcaption>UML Diagram: Singleton Pattern</figcaption>
</figure>

</details>


<details>
	<summary> Use Cases </summary>

The Singleton pattern is useful in situations where we need to ensure that there is only one instance of a class and that instance needs to be globally accessible. Here are some common use cases where the Singleton pattern can be applied:

1. **Logging:** <br> In a logging system, you may want to have a single point of access to the logger instance throughout the application. The Singleton pattern ensures that the logger is instantiated only once and can be accessed globally to write log messages.
2. **Database Connections:** <br> When managing database connections, it's often desirable to have a single instance of a connection manager that handles creating, pooling, and distributing connections. The Singleton pattern can be used to ensure that there is only one connection manager instance in the system.
3. **Configuration Settings:** <br> In an application with global configuration settings, such as application-level properties or environment variables, the Singleton pattern can be used to provide a single access point to the configuration settings. This allows easy and consistent access to the settings from different parts of the application.
4. **Caching:** <br> A caching system can benefit from using the Singleton pattern to ensure that there is only one cache manager instance. This allows different components of the system to use the same cache and avoid duplicate caching logic.
5. **Thread Pools:** <br> In scenarios where you need to manage a pool of worker threads, the Singleton pattern can be used to provide a single point of access to the thread pool. This ensures that all components that require thread execution share the same pool.
6. **GUI Components:** <br> In graphical user interface (GUI) applications, certain components such as dialog boxes or menu managers may need to be globally accessible. The Singleton pattern can be applied to ensure that there is only one instance of these components, simplifying their usage and management.

It's important to note that while the Singleton pattern offers benefits in certain scenarios, it should be used judiciously. Overusing singletons can lead to tight coupling and make testing and maintenance more difficult. It's important to evaluate whether a singleton is the most appropriate design choice for your specific use case and consider other alternatives if necessary.

</details>

<details>
	<summary> Example Code </summary>

```java
class Singleton {
	private static Singleton instance;

	private Singleton() {
		// Private constructor to prevent direct instantiation
	}

	public static Singleton getInstance() {
		if (instance == null) {
			instance = new Singleton();
		}
		return instance;
	}

	// Other methods and properties of the Singleton class
}

public class Main {
	public static void main( String[] args ) {
		Singleton singleton = Singleton.getInstance();
	}
}
```

</details>

<details>
	<summary> Benefits and Considerations </summary>

- Ensure that only one instance of the class exists.
- Provides a global point of access to the instance, allowing other parts of the system to easily use and share the same instance.
- Lazily initializes the instance only when it is first requested.
- Can be used to manage resources that should have a single point of control, such as database connections or thread pools.
- However, it is important to consider thread safety and potential performance impacts in multi-threaded environments.

</details>

<details>
	<summary> Implementation Steps </summary>

1. Create a private static member variable in the Singleton class to hold the single instance of the class.
2. Make the constructor of the class private to prevent direct instantiation from outside the class.
3. Create a public static method that acts as a global access point to the single instance of the class.
4. Within the static method, check if the instance already exists. If it does, return the existing instance. If not, create a new instance and return it.
5. Use the public static method to access the Singleton instance throughout the application.

</details>

<details>
	<summary> Note </summary>

The Singleton pattern is a powerful tool but should be used judiciously. Overusing singletons can lead to tight coupling and make testing and maintenance more difficult. It's important to evaluate whether a singleton is the most appropriate design choice for your specific use case.

</details>

<details>
	<summary> External Links </summary>

- [Refactoring Guru: Singleton](https://refactoring.guru/design-patterns/singleton)

</details>



### Prototype Pattern - A Creational Design Pattern

<details>
	<summary> Overview </summary>

The Prototype pattern is a creational design pattern that allows you to create copies of objects without coupling your code to their concrete classes. It provides a mechanism for creating new objects by copying an existing object, known as the prototype, and modifying it as needed. This pattern promotes flexibility and reusability by abstracting the process of object creation.

</details>

<details>
	<summary> Intent </summary>

The intent of the Prototype pattern is to enable the creation of new objects by cloning existing objects, thus avoiding the need for explicit instantiation and reducing the dependency on specific classes.

</details>

<details>
	<summary> Key Components </summary>

1. **Prototype:** <br> Defines the interface for cloning itself.
2. **Concrete Prototype:** <br> Implements the cloning interface and provides the cloning behavior.
3. **Client:** <br> Requests the cloning operation and works with the cloned objects.

</details>

<details>
	<summary> UML Diagram </summary>

<figure>
    <img src="https://refactoring.guru/images/patterns/diagrams/prototype/structure-indexed.png"
         alt="UML Diagram, Prototype Pattern">
    <figcaption>UML Diagram: Prototype Pattern</figcaption>
</figure>

</details>


<details>
	<summary> Use Cases </summary>

The Singleton pattern is useful in situations where we need to ensure that there is only one instance of a class and that instance needs to be globally accessible. Here are some common use cases where the Singleton pattern can be applied:

1. **Object Creation Cost Reduction:** <br> When creating objects is an expensive operation in terms of time, resources, or complex initialization, the Prototype pattern allows you to create new instances by cloning existing objects. This approach avoids the overhead of costly object creation processes, such as querying a database, making network calls, or performing complex calculations.
2. **Flexibility and Customization:** <br> The Prototype pattern allows you to create new objects with slight variations or customization while reusing existing object structures. By cloning a prototype and modifying its properties, you can tailor the new object to specific requirements without the need to create a new class or write complex initialization logic.
3. **Immutable Objects:** <br> If you have immutable objects, meaning objects whose state cannot be modified once created, the Prototype pattern is useful for creating new instances with different initial values. Instead of creating separate immutable classes for each variation, you can clone an existing object and adjust the required properties.
4. **Prototype Registry or Factory:** <br> The Prototype pattern can be used to implement a prototype registry or factory. Instead of relying on traditional factory methods, you can register and manage a set of prototypes in a centralized registry. Clients can request the creation of new objects by cloning the appropriate prototype from the registry, allowing for more flexibility and dynamic object creation.
5. **Dynamic Configuration:** <br> The Prototype pattern enables dynamic configuration of objects at runtime. Instead of configuring objects manually or using external configuration files, you can use prototypes to clone pre-configured objects and customize them as needed. This approach is particularly useful when dealing with complex configuration scenarios or when configuration changes frequently.
6. **State Restoration:** <br> Prototypes can be used for state restoration purposes. By storing snapshots of object states as prototypes, you can easily revert objects to a previous state by cloning the respective prototype. This can be valuable in scenarios where you need to roll back or undo changes made to objects.

These are some common use cases of the Prototype pattern, demonstrating its flexibility and advantages in object creation and customization.

</details>

<details>
	<summary> Example Code </summary>

```java
// Prototype interface
interface Prototype {
    Prototype clone();
}

// Concrete prototype
class ConcretePrototype implements Prototype {
    private String property;

    public ConcretePrototype(String property) {
        this.property = property;
    }

    @Override
    public Prototype clone() {
        return new ConcretePrototype(this.property);
    }
}

// Client
public class Client {
    public static void main(String[] args) {
        Prototype prototype = new ConcretePrototype("Prototype");
        Prototype cloned = prototype.clone();
    }
}

```

</details>

<details>
	<summary> Benefits and Considerations </summary>

**Benefits:**
- Allows adding and removing products dynamically at runtime.
- Avoids subclassing by cloning existing objects.
- Provides a flexible and reusable way to create objects

**Consideration:**
- Deep copying might be required if the prototype contains complex nested objects.
- Properly handling the cloning process to maintain the integrity of the cloned objects.

</details>

<details>
	<summary> Implementation Steps </summary>

1. Define the **Prototype** interface.
2. Implement the **ConcretePrototype** class that implements the **Prototype** interface and provides cloning behavior.
3. Create a **client** that uses the Prototype objects and requests cloning as needed.

</details>

<details>
	<summary> Note </summary>

It's important to ensure that the prototype objects are correctly cloned to avoid unintended sharing of internal states between clones.

</details>

<details>
	<summary> External Links </summary>

- [Refactoring Guru: Prototype](https://refactoring.guru/design-patterns/prototype)

</details>












