# SOLID PRINCIPLES

- S - SINGLE RESPONSIBILITY PRINCIPLE
- O - OPEN/CLOSED PRINCIPLE
- L - LISKOV'S SUBSTITUTION PRINCIPLE
- I - INTERFACE SEGREGATION PRINCIPLE
- D - DEPENDENCY INVERSION PRINCIPLE

## SINGLE RESPONSIBILITY PRINCIPLE :
This principle states that **a class should have only one reason to change**. That means a class should hold only one responsibility.

## OPEN/CLOSED PRINCIPLE
This principle states that a class should be **open for extension but closed for modification**.
This means that we should not modify any class which already has single responsibility. 
Instead, we should extend it using interface or abstract classes.
This makes the existing code sperate from modified code and thus provides easier maintainability.

## LISKOV'S SUBSTITUTION PRINCIPLE
If class A is parent of class B, then class B should be able to replace **class A at any place without disturbing the behaviour of the code**.
This means that a child should extend all the capabilities of a parent and not narrow it down.

## INTERFACE SEGREGATION PRINCIPLE
Interfaces should not have unnecessary functions which are not required by the client. 
This principle is similar to single responsibility principle, but for interfaces.
**Its better to have short and segmented interfaces**.

## DEPENDENCY INVERSION PRINCIPLE
This principle states that a class should be dependent on interfaces or abstract classes and not on other concrete class.
This reduces tight coupling and makes classes loosly coupled using the concept of abstraction.

