## Suggestions for Object Oriented Design

Whenever writing code in an object-oriented language, sticking to the following list of suggestions will make your code amenable to changes with the least effort.

1. **Separate out parts of code that vary or change from those that remain the same.**

    For example, if you have a class representing different shapes, separate the code for calculating area and perimeter, as these behaviors may vary for different shapes.

2. **Always code to an interface and not against a concrete implementation.**

    Instead of relying on specific implementations, define interfaces and write code that depends on these interfaces. This allows you to switch implementations without changing the calling code.

3. **Encapsulate behaviors as much as possible.**

    Encapsulating behaviors within classes ensures that they are well-contained and can be easily modified or extended without affecting other parts of the codebase.

4. **Favor composition over inheritance.**

    Instead of creating complex class hierarchies through inheritance, prefer composing classes by using smaller, reusable components. This promotes flexibility and avoids tight coupling.

5. **Interacting components within a system should be as loosely coupled as possible.**

    Reduce direct dependencies between classes and modules. Use interfaces and dependency injection to achieve loose coupling, making it easier to change or replace components.

6. **Ideally, class design should inhibit modification and encourage extension.**

    Design classes in a way that adding new features or behaviors doesn't require modifying existing code. Use open-closed principle and interfaces to enable extension without modification.

7. **Using patterns in your day-to-day work allows exchanging entire implementation concepts with other developers via shared pattern vocabulary.**

    Design patterns provide common solutions to recurring design problems. Using them not only simplifies communication among developers but also promotes code reuse and maintainability.
