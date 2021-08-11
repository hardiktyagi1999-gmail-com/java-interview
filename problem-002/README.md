### Problem Statement

This problem expects an implementation using Java's inheritance and encapsulation concepts.

### Pre-requisites

1. Java 8 (Change the jdk.version in pom.xml if you want to use a different java version)
2. Maven for setting up compilation and builds for the project.
3. git for committing code.
4. A Text Editor or an IDE such as Eclipse, VS Code or IntelliJ Idea.

### Objects or artifacts to be created

1. Project structure will follow Maven's project structure for java projects.
2. This project intends to evaluate the area and perimeter of different shapes such as Rectangle, Square and Circle.
3. Create Classes for Rectangle, Square and Circle. The necessary inputs for each of the shapes need to be taken as constructor arguments.
4. All Shapes need to have an implementation of methods area and perimeter.
5. A sample App.java and AppTest.java has been provided.
6. The App.java needs to create a method named `computeProperties` which will take either a Rectangle, Square or a Circle as an input argument.
7. The `computeProperties` method needs to print the area and perimeter for the shape object being passed to the method.
8. Write unit tests using JUnit to assert area and perimeter for each of the Shape objects.

### Expectations

1. All Shapes Rectangle, Square and Circle needs to have common methods area and perimeter. This can be solved using Java inheritance concept.
2. The `computeProperties` method in App.java needs to take any Shape that is possible. This can be solved using Java polymorphism concept.
3. We expect unit tests to thoroughly test both the area and perimeter functions of all the Shapes.