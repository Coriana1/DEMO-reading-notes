# Redux Toolkit (RTK)
1. What concerns are addressed by Redux Toolkit?
  - * Simplifying the Redux setup and configuration process.
    * Providing a set of utilities and helpers to reduce boilerplate code.
    * Encouraging best practices for Redux development.
    * Integrating commonly used Redux libraries, such as Redux DevTools and Redux Thunk, by default.
2. What does configureStore() do?
  - A function provided by Redux Toolkit that combines several Redux store setup steps into a single function call. It helps simplify the store configuration process by automatically setting up the store with sensible defaults and enabling common Redux middleware.
3. How would I use createSlice()?
  - * Import createSlice from Redux Toolkit.
    * Define an initial state object for the slice.
    * Define a set of reducer functions, each corresponding to a specific action, using the reducer field in the slice definition.
    * Optionally, define additional extraReducers to handle actions that are not specific to the slice.
    * Call createSlice() with the slice configuration object to generate the slice object with automatically generated action creators and a reducer.

## MobX
1. What is Mobx?
  -  A state management library for JavaScript applications. It allows developers to create reactive applications by automatically tracking and updating the state based on changes in observed values.
2. How does MobX make it “impossible” to produce an inconsistent state?
  - MobX ensures that the state remains consistent by tracking the dependencies between observables (values that are being observed for changes) and reactions (code that depends on the observables). When an observable value changes, MobX automatically triggers the reactions that depend on it, ensuring that the state is always in a consistent and up-to-date state.
3. How would we build a reactive user interface?
  - * Define observable state variables using MobX decorators or the observable() function.
    * Use computed values (@computed decorator or computed() function) to derive new values based on the observable state.
    * Create actions that modify the state using MobX decorators (@action, @action.bound, etc.) or the action() function.
    * Build the user interface components that observe the state and automatically update when the state changes, leveraging MobX's reactive capabilities.

### Tutorial
1. What take-away(s) did this tutorial provide?
  - Great quick start references that provide an in-depth description of the correct way to use Redux and guide you through the building process of Redux.

### Reflection
1. What are your learning goals after reading and reviewing the class README?
  - Gain hands-on experience in building a complete React/Redux application and migrating simple Redux code to Ducks or Redux Toolkit.