# CSD Topics
## TDD: Test Driven Development
1. Red : write small failing tests
2. Green : write small amount of passing code
3. Refactor : improve the code
## Unit Testing

- Define the behavior of production code
- Single module only
- Isolates behavior
- Reusable
- Should be FIRST
   - **F**ast
   - **I**solated
   - **R**epeatable
   - **S**elf-verifying
   - **T**imely

## SOLID Principles

- Single Responsibility Principle

   - Each function should only have one responsibility as well as each module
- Open Closed Principle

   - Software entities (functions) should be open for extension, but closed for modification


- Liskov Substitution Principle (ES 2015+)

   - Derived classes must be substitutable for their base classes. Code to abstraction

- Interface Segregation Principle (TypeScript)

   - Clients should not be forced to depend upon interfaces that they do not use
   - Interfaces are interchangeable with option hashes

- Dependency Inversion Principle (TypeScript)

   - Depend on abstractions, not on concretions

## Code Smels

1. Duplicate code
2. Long methods
3. Big classes/files
4. Empty catch clauses
5. Significant use of statics/globals
6. Variables with wide scope
7. Poorly named variables
8. Switch or with statements
9. Unnecessary complexity
10. Comments