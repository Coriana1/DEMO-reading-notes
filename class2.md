# React lifecycle
1. Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?
  - *Render* first then *componentDidMount*
2. What is the very first thing to happen in the lifecycle of React?
  - Mounting phase - component is initialized and inserted into the DOM 
3. Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates
  - **Constructor, Render, ComponentDidMount, React Updates, ComponentWillUnmount**
4. What does componentDidMount do?
  - Handling all network requests and setting up subscriptions during the mounting phase

## React State Vs Props
1. What types of things can you pass in the props?
  - Objects, arrays, and functions.
2. What is the big difference between props and state?
  -  State is owned locally and the component itself updates it. Props are owned and read-only by a parent. 
3. When do we re-render our application?
  - When React needs to update the app with some new data
4. What are some examples of things that we could store in state?
  - User interface (UI), form input, data from API