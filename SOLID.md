SOLID principles - Object-Oriented Programming

### Single Responsibility
- Class should have things that only change for the same reason.
- You can usually detect violations by finding _God Objects_ Classes that know too much or do too much.
- SRP has great benifit on limiting the impact of change.

### Open/Closed Principle
Classes are:
- **Open for extension**
  - We can add a new feature to our system.
- **Closed for modifications**
  - We don't have to modify how the code works.

This can be achieved by following the Strategy Pattern and Dependency Injection.

### Liskov Substitution
- You should be able to replace an instance of a class with an instance of its subclass without breaking anything.
- Subclasses should respect the same interface of the parent class.

### Interface Segregation
- Client should not have to depend on methods which it does not use.

### Dependency Inversion
- Our high level objects don't need to depend on how our low level objects are implemented.
- If it quacks like a duck, it's a duck.
