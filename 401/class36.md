# Dan Abramov Redux Tutorials
1. What is the first principle of Redux?
  - The entire state of an application is stored in a single JavaScript object called the "store." This makes it easier to manage and track changes to the state.
2. what is a store and what do we use our reducers for within that store?
  - An object that holds the complete state tree of an application. Reducers are used within the store to specify how the state should be updated in response to different actions. Reducers are pure functions that take the current state and an action as arguments, and return a new state based on the action.
3. Name three Redux store methods given to us by createStore and describe their use.
  - **getState()**: Returns the current state of the store.
    **dispatch(action)**: Dispatches an action to trigger the state update process.
    **subscribe(listener)**: Adds a listener function that will be called whenever the state changes. 
4. Explain to a non-technical recruiter what combineReducers() does and why it is useful.
  - Imagine you have a big puzzle to solve, but instead of trying to put all the pieces together at once, you decide to break it down into smaller sections. Each section represents a different part of the puzzle, like the sky, the mountains, or the trees.

Now, let's say you have a group of friends helping you solve the puzzle. Each friend specializes in a specific section. One friend is great at putting together the sky pieces, another is skilled at the mountains, and so on.

In programming, when we talk about Redux, it's like solving a puzzle with the help of our friends. The puzzle represents the state of our application, which is all the data that needs to be managed. The friends represent the different parts of the state that we want to handle separately.

Now, to make it easier to work with our friends and combine their efforts, we use something called combineReducers(). This function helps us bring together the work of our friends and create a single solution.

## Additional Questions
1. Looking ahead at this module’s course schedule, What do you look forward to learning?
  - Diving into server-side and client-side JavaScript, work with UI component frameworks, and explore cloud infrastructure and AWS services for building scalable backend infrastructure.
2. What are your learning goals after reading and reviewing the class README?
  - Understand the purpose and benefits of using Redux for global state management in React applications.