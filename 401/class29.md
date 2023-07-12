# Extracting State Logic into a Reducer
1. What is the motivation for adding a reducer?
  - to provide a more structured and scalable way to manage complex state transitions and logic in components
2. What are actions in the context of a reducer? How are they different than setting state directly?
  - Actions are plain JavaScript objects that describe a state change or an intention to update the state. Actions are different from setting state directly because they provide a clear and consistent way to describe state updates in a centralized manner. By dispatching actions to the reducer, the logic for state updates can be encapsulated within the reducer function, making it easier to reason about and track state changes.
3. What common list operation is useReduce named for, and why?
  - Reduce - used to transform a list into a single value by applying a function to each element of the list, accumulating the results into a final value.
4. When should you switch from useState to useReducer?
  - When the complexity of your state management increases.

# Reflection
What are your learning goals after reading and reviewing the class README?
  - Be able to apply the useReducer() hook and the reducer pattern to manage complex state transitions in functional components effectively.