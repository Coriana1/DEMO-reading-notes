# useEffect hook
1. What is the main intended use case for the useEffect hook?
  - To perform side effects in functional components. Side effects include things like data fetching, subscriptions, or manually manipulating the DOM. It allows you to handle these side effects in a declarative and centralized manner within the functional component.
2. How does the effect’s logic interact with the component?
  - By running after the component has rendered and updated. When the component mounts, the effect is executed, and it can perform actions such as subscribing to events, fetching data, or modifying the DOM
3. What is the importance of the return value from the effect’s logic function?
  - It allows you to specify cleanup actions. If the effect needs to clean up after itself (e.g., canceling a subscription, removing event listeners), you can return a function from the effect. This cleanup function will be executed when the component unmounts or when the effect is re-run due to dependencies being updated. It ensures that the effect's side effects are properly managed and cleaned up when they are no longer needed.

## Reflection
1. What are your learning goals after reading and reviewing the class README?
  - Gain a deeper understanding of how to use the effect hook to set up event listeners and handle cleanup.