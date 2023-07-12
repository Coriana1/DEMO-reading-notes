# Thinking in React
1. What is one reason a local variable isn’t sufficient for managing a React component?
  - Local variables are scoped within the component and do not persist between renders. When a component re-renders, the local variables are re-initialized, losing their previous values. 
2. What is the argument to the useState hook, and what are the two parts of its return array?
  - The initial value of the state. It can be any valid JavaScript value, such as a number, string, object, or array. The useState hook returns an array with two elements: the current state value and a function to update the state. The first element of the array (current state value) is typically assigned to a variable, while the second element (state update function) is used to modify the state.
3. How can Component A access state from Component B?
  - Component communication can be achieved through props. If Component B needs to share its state with Component A, Component A can pass a prop to Component B that represents the shared state value. Component B can then update the shared state by invoking a function provided by Component A through props. 

Reflection
1. What are your learning goals after reading and reviewing the class README?
  - Gain knowledge about the lifecycle of a React component.