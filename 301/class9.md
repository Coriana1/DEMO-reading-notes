# Functional Programming Concepts

What is functional programming?
  - A different way of programming that leadS to more modular, maintainable, and scalable code by focusing on writing code in a declarative style, where the emphasis is on describing what computations should be performed rather than how to perform them. .
What is a pure function and how do we know if something is a pure function?
  - Function that gives the same input & always returns the samme output, and doesn't have any side effects (no mods to any outside data of its local scope)
    - Something is a pure function if it doesn't modify any data outside it's local scope, isn't mutable data, functions doesn't depend on global stae, and function doesn't retunr same output for the sane input everythimg is called
What are the benefits of a pure function?
  - Reusability, caching, predictable behavior, no side effects, parrallelism
What is immutability?
  - A property of data that refers to its inability to be changed after it has been created.
What is Referential transparency?
-  A property of functions that means that a function call can be replaced with its resulting value without affecting the behavior of the program.

## Node JS Tutorial for Beginners #6 - Modules and require()
What is a module?
  - A self-contained unit of code that can be imported and used in other parts of a program - *functions, classes, constants, and other data structures, as well as its own private state and behavior.*
What does the word ‘require’ do?
  - load and use modules or external dependencies in a program by searching for a module with the specified name and loads it into the current program
How do we bring another module into the file the we are working in?
  - Using an import statement
What do we have to do to make a module available?
  - Export its functions, classes, and data structures that you want to make accessible