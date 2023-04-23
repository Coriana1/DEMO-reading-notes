# React Docs - Thinking in React
1. What is the single responsibility principle and how does it apply to components?
  - SRP - a software design principle that states that a component, class, or module should have only one reason to change or job to perform. 
2. What does it mean to build a ‘static’ version of your application?
  - Creating a version of the application that doesn't rely on server-side processing or dynamic content generation.
3. Once you have a static application, what do you need to add?
  - Client-side interactions, serverless functions, APIs, content management, and deployment pipelines
4. What are the three questions you can ask to determine if something is state?
  - **Is the behavior being affected within the app?** 
    **Is there something that needs to be rememebered between different user interactions and app sessions?**
    **Are there any changes overtime?**
5. How can you identify where state needs to live?
  - Identify the components that need state, Determine the scope of the state, Choose the appropriate level of abstraction for the state, based on the scope and complexity of the state, Consider the relationship between components.  
## Higher-Order Functions
1. What is a “higher-order function”?
  - A function that takes one or more functions as arguments or returns a function as its result.
2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?
  - Defining a new function that will be returned by the greaterThan function, which compares a given value with the threshold value to determine whether the value is greater than the threshold
3. Explain how either map or reduce operates, with regards to higher-order functions.
  -  Function takes an array and a function as its arguments and returns a new array where each element of the original array has been transformed by the provided function.