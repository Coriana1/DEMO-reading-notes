# React Docs - Forms
1. What is a ‘Controlled Component’?
  -  An input form element whose value is controlled by React  
2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
  -We should update the state with the user's responses so that the sate and user-input is kept in sync.
3. How do we target what the user is entering if we have an event handler on an input field?
  - Accessing the value property of the event object in the event handler function

## The Conditional (Ternary) Operator Explained
Why would we use a ternary operator?
  - Writing conditional statements - allows to write more concise code
Rewrite the following statement using a ternary statement:
console.log(true);
} else {
console.log(false);
}