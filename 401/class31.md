# Choosing the State Structure
1. Summarize the five principles for structuring state.
  - * Single source of truth: Maintain a single, centralized store for all state in your application.
    * State is read-only: State should be immutable and only updated through well-defined actions.
    * Changes are made with pure functions: Use pure functions (reducers) to update the state based on actions.
    * State updates are predictable: Given the same inputs, the state updates should always produce the same results.
    * Use normalized state shape: Organize the state in a normalized and structured way that suits your application's needs.

## Passing State Deeply with Context
1. What problem do Contexts aim to solve?
  - Prop drilling - the need to pass data through multiple levels of components without directly using props. Contexts provide a way to share state across the component tree without explicitly passing it down through each component.
2. What is one technique to try before useContext?
  - Prop drilling approach - involves passing down the necessary state or data as props through the component hierarchy.
3. What hook complements useContext for complex applications?
  - The useReducer hook complements useContext for complex applications. useReducer provides a way to manage more complex state logic by combining state management with dispatching actions. 