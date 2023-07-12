# Reading
1. What are the building blocks of a React app? 
  - Compoents, JSX, state, props, virtual DOM, lifecyle methods, react router, 
2. What is the difference between an HTML element and a React component?
  - HTML elements are static building blocks defined by the HTML specification, while React components are dynamic, reusable, and encapsulated pieces of UI code with built-in logic and interactivity. 
3. What is JSX and why do we use it?
  - JavaScript XML - an extension to the JavaScript language syntax that allows you to write HTML-like code within JavaScript. 
    * Used for - Declarative Syntax, Integration of JavaScript and HTML, Component-Based Development, Efficient Rendering, Static Type Checking, Familiarity and Readability

4. Describe the process of embedding JavaScript expressions in JSX.
  - Basic Expression:
You can embed a JavaScript expression by placing it within curly braces. For example:

  const name = "John Doe";
  const greeting = <h1>Hello, {name}!</h1>;
  In this example, the value of the name variable is dynamically inserted into the JSX markup, resulting in the rendered output: <h1>Hello, John Doe!</h1>.

Inline JavaScript Logic:
You can also include more complex JavaScript logic within curly braces. For example:

  const isLoggedIn = true;
  const greeting = <div>{isLoggedIn ? <p>Welcome back!</p> : <p>Please log in.</p>}</div>;
  In this example, the conditional expression {isLoggedIn ? <p>Welcome back!</p> : <p>Please log in.</p>} is used to conditionally render different content based on the value of the isLoggedIn variable. The resulting output will vary depending on the value of isLoggedIn.

Accessing JavaScript Variables and Functions:
You can access JavaScript variables and functions within JSX by using curly braces. For example:

  const count = 10;
  const doubleCount = () => count * 2;
  const message = <p>The count is: {count}, and the double count is: {doubleCount()}.</p>;
  In this example, the values of the count variable and the doubleCount function are accessed within the JSX markup. The resulting output will display the current value of count and the result of doubleCount().

5. Does React or JSX have any special features for iteration or conditional logic?
  - Yes 
6. How does React know to respond to a user’s inputs?
  - By attaching event handlers to elements or components and using its synthetic event system to trigger the corresponding event handlers when the specified events occur.
7. What word indicates that a React component manages data with a Hook?
  - useState
8. How can two react components share data?
  - Parent-to-Child Communication, Child-to-Parent Communication, Sibling Components Communication, Using React Context, Using External State Management Libraries

## Render and Commit
1. What are the three steps of refreshing a React UI?
  - **Receiving new props or state**: React compares the new props or state with the previous ones to determine if a re-render is necessary.
    **Reconciliation**: React performs a virtual DOM diffing process to identify the differences between the current virtual DOM and the new virtual DOM representation of the component.
    **Updating the actual DOM**: React applies the necessary changes to the real DOM based on the differences identified during the reconciliation step.
2. How do you trigger updates to a component after the initial render?
  - You can use the setState method or hooks like useState or useReducer to update the component's state. 
3. Does React recreate DOM nodes on every rerender?
  - No, React does not recreate DOM nodes on every re-render.
4. After React has updated the DOM, what still needs to happen before the user sees the change?
  - The browser needs to perform the painting step to reflect the changes visually to the user

### Additional Questions
1. Note the naming conventions in the Airbnb React/JSX Style Guide. What pattern(s) do you see?
  - Component names, files names, varibale and function names, props names, CSS Class names 
2. Looking ahead at this module’s course schedule, What do you look forward to learning?
  - relearning compenents and writing some new markup 
3. What are your learning goals after reading and reviewing the class README?
  - Familiarize yourself with SASS (Syntactically Awesome Style Sheets) and its features such as nesting and variables for styling React applications.