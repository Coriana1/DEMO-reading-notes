# async actions
1. Why use Redux middleware?
  - Provides a way to add custom functionality to the Redux dispatch process. It allows us to intercept actions before they reach the reducers and perform additional tasks such as handling async operations, logging, or modifying actions.
2. Consider the Redux Async Data Flow Diagram. Describe the flow in your own words.
  - In the Redux Async Data Flow, actions are dispatched and intercepted by middleware, which can perform async operations and modify the actions before reaching the reducers. The reducers then update the state based on the actions, and the updated state triggers re-rendering of connected components.
3. How are we accommodating async in our Redux app?
  - By using middleware such as Redux Thunk. Redux Thunk allows us to write action creators that return functions instead of plain action objects. 

## thunk middleware
1. Why would you need redux-thunk middleware?
  - When we want to dispatch actions that involve async operations, such as API requests. Redux Thunk allows us to write action creators that can return functions instead of plain action objects, enabling us to handle async logic and dispatch multiple actions in a synchronous-looking way.
2. Redux Thunk middleware allows you to write action creators that return a  **function** instead of an action.
3. Describe how any return value from the inner thunk function will be made available.
  - Through the use of promises or by using async/await syntax. When the inner thunk function completes, it can resolve a promise or return a value that can be accessed in the code that dispatched the thunk action.

### Reflection
1. What are your learning goals after reading and reviewing the class README?
  - To understand the purpose and usage of Redux middleware, specifically Thunk middleware, in handling asynchronous actions in a Redux application.