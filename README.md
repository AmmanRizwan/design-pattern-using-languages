# design-pattern-using-java

This repository is create to understand the design pattern used in building an efficient application. It will help to avoid redundancy and write a clean code.

### Creational Patterns

Deals with object creation.

1. **Singleton**

> Ensures a class has only one instance and provides a global access point.

*Example: Logging, Database Connection, Caching* 

2. **Factory Method**

> Defines an interface for creating objects, but lets subclasses decide which class to instantiate.

*Example: Frameworks, extensible libraries.*

3. **Abstract Factory**

> Creates families of related objects without specifying their concrete classes.

*Example: UI toolkits (different themes), cross-platform apps.*

4. **Builder**

> Separates object construction from its representation.

*Example: Constructing complex objects (e.g. query builders, HTTP requests)*

5. **Prototype**

> Creates new objects by copying an existing object.

*Example: Expensive object creation scenarios.*

### Structural Patterns

Deal with object composition and structure.

1. **Adapter**

> Allows incompatible interfaces to work together.

*Example: Integrating third-party libraries.*

2. **Decorator**

> Adds behavior to objects dynamically without modifying their code.

*Example: Middleware, logging, validation layers.*

3. **Facade**

> Provides a simplified interface to a complex subsystem.

*Example: API wrappers, service layers.*

4. **Proxy**

> Provides a placeholder for another object to control access.

*Example: Lazy loading, access control, remote services.*

5. **Composite**

> Treats individual objects and compositions uniformly.

*Example: Tree structures (UI components, file systems).*

### Behavioral Patterns

Deal with communication between objects

1. **Observer**

> Defines a one-to-many dependency so when one object changes state, all dependents are notified.

*Example: Event systems, UI updates*

2. **Strategy**

> Defines a family of algorithms and makes them interchangeable.

*Example: Payment methods, sorting strategies.*

3. **Command**

> Encapsulates a request as a object.

*Example: Undo/redo systems, task queues.*

4. **State**

> Allows an object to change its behavior when its internal state changes.

*Example: Workflow engines, state machines*

5. **Template Method**

> Defines the skeleton of an algorithm in a method but lets subclasses override steps.

*Example: Framework base classes.*

### Software Architectural Patterns

1. **MVC - (Model-View-Controller)**

> MVC separates an application into three components:
>
> - Model        -> Business logic + data
> - View         -> UI (what the user sees)
> - Controller   -> Handles user input and coordinates between Model and View.

2. **MVVM - (Model-View-ViewModel)**

> MVVM improves on MVC, especially for UI-heavy applications.
> - Model       -> Data + business logic
> - View        -> UI
> - View Model  -> Connects View and Model, handles UI logic

3. **Repository Pattern**

> The Repository Pattern abstracts data access logic.

4. **Dependency Injection (DI)**

> Instead of a class creating its own dependencies, they are injected from outside.

5. **Event-Driven Architecture (EDA)**

> Components communicate using events, not direct calls.

6. **Microservices Architecture**

> Instead of building one big application (monolith), you build many small independent services.

