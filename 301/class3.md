# React Docs - lists and keys
What does .map() return? 
  -A map object
If I want to loop through an array and display each value in JSX, how do I do that in React?
  - .map() method and return a new array of JSX elements
Each list item needs a unique **key prop**.
What is the purpose of a key?
  - Shows which items in a list have changed, been added, or been removed.

## The Spread Operator
What is the spread operator?
  - Quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.
List 4 things that the spread operator can do.
  - *Adding an item to a list*
    *Adding to state in React*
    *Concatenating or combining arrays*
    *Using Math functions*
Give an example of using the spread operator to combine two arrays.
  - const cars = ['🚗', '🚙'];
   const trucks = ['🚚', '🚛'];
  result  const combined2 = [...cars, ...trucks];
Give an example of using the spread operator to add a new item to an array.
  - const myArray = [1, 2, 3];
// add the number 4 to the end of the array
const newArray = [...myArray, 4];
console.log(newArray); // Output: [1, 2, 3, 4]
Give an example of using the spread operator to combine two objects into one.
Videos
  - const obj1 = { a: 1, b: 2 };
    const obj2 = { c: 3, d: 4 };
    const combinedObj = { ...obj1, ...obj2 };
    Output: { a: 1, b: 2, c: 3, d: 4 }

## How to Pass Functions Between Components
In the video, what is the first step that the developer does to pass functions between components?
  - Created 'increment' function and pass in a 'name' variable called 'ppl' assigned it 'this.state.people.map()', passed in 'P' object for person, then did 'if(p.name === name) {p.count++;} and then return p


In your own words, what does the increment function do?
  - Determines the next node at the same level
How can you pass a method from a parent component into a child component?
  - The method as a prop in the child component.
How does the child component invoke a method that was passed to it from a parent component?
  - By calling the method through the props.