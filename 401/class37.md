# Multiple Reducers Example
1. Why create multiple reducers?
  - To handle different slices of the application state. Each reducer focuses on a specific part of the state, making it easier to manage and reason about the state changes. By dividing the state into smaller, modular pieces, it improves code organization and allows for better separation of concerns.
2. How would you combine multiple reducers?
- Redux provides a utility function called combineReducers(). This function takes an object as an argument, where each key represents a slice of the state and the corresponding value represents the reducer function for that slice. The combineReducers() function then returns a single root reducer that can be used with the Redux store.
2. How will you manage state as an immutable object? Why?
- As an immutable object - the state should not be directly modified but rather replaced with a new state object whenever changes are made. 

## Redux Docs: Using Combined Reducers
1. combineReducers is a utility function to simplify the most common use case when writing **Redux applications**.
2. Explain how combineReducers assembles the new state tree.
  - When combineReducers() is called with an object of reducers, it creates a new root reducer. This root reducer manages the overall state tree of the application. Whenever an action is dispatched, the root reducer delegates the responsibility of handling the action to the corresponding slice reducer based on the key-value mapping provided. Each slice reducer updates its specific portion of the state, and the root reducer combines all the updated slices into a new state object, forming the new state tree.
3. How would you define initial state in an app using combineReducers?
  - Each individual reducer is responsible for defining its own initial state. The initial state can be defined within each reducer file using the ES6 default parameter syntax. For example:

## Redux Docs: Combined Reducer Syntax
1. Why will you want to split your reducing functions as your app becomes more complex?
  - As an app becomes more complex, splitting reducing functions becomes beneficial for better code organization and maintainability. 
    - Splitting reducers allows you to handle different parts of the state separately, making it easier to reason about each slice of the state and keep the logic focused. It also enables code reuse and modularity, as different reducers can be developed and modified independently.
2. The **combineReducers** helper function turns an object whose values are different reducing functions into a single reducing function you can pass to **the Redux store**.
3. What is a popular convention when naming reducers?
  - Use descriptive names that indicate the specific slice of state they are responsible for. 

### Reflection
1. What are your learning goals after reading and reviewing the class README?
  - Be aware of the considerations and potential unintended consequences when multiple reducers respond to the same action.
