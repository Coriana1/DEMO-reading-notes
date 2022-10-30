# Class 03 Lecture Notes

## Arrays

1. When should you use an unordered list in your HTML document? create a list in no particular order.
2. How do you change the bullet style of unordered list items? use the STYLE attribute, set its value as “list-style-type:format” where format is the word circle, square or disc. && You add the STYLE attribute within the <ul> start tag.
3. When should you use an ordered list vs an unorder list in your HTML document? Unordered list to create a list in no particular order. Ordered list to create a list in a specific order
4. Describe two ways you can change the numbers on list items provided by an ordered list? value attribute changes the number of a specific list item and the ones that follow.

## Learning CSS 
1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”? A margin is the space around an element's border, while padding is the space between an element's border and the element's content. So with The Box Model padding, margin and border will cause other elements to be pushed away from the box.
2. List and describe the four parts of an HTML elements box as referred to by the box model.
  - Content box: Where your content is displayed
  - Padding box: Sits around the content as white space
  - Border box: Wraps the content and any padding
  - Margin box: Outermost layer, wrapping the content, padding, and border as whitespace between this box and other elements
## Learning JS
1. What data types can you store inside of an Array?simple reals or integers, vectors, matrices, or other arrays. Also a Away to store sequences of integers, and some functions in Stan, such as discrete distributions, require integer arguments.
2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?
3. List five shorthand operators for assignment in javascript and describe what they do.
    - Assignment -  assign a value to a variable -  x = f()	
    - Addition assignment	- adds the value of the right operand to a variable and assigns the    result to the variable -  x += f()	
    - Subtraction assignment - subtracts the value of the right operand from a variable and assigns the result to the variable -   x -= f()	
    - Multiplication assignment -	multiplies a variable by the value of the right operand and assigns the result to the variable -  x *= f()	
    - Division assignment - divides a variable by the value of the right operand and assigns the result to the variable  -  x /= f()	
4. Read the code below and evaluate the last expression and explain what the result would be and why.
5. Describe a real world example of when a conditional statement should be used in a JavaScript program. A password they are “if, then” logic statements: If a user enters the correct password, then they can access the program.
6. Give an example of when a Loop is useful in JavaScript. If you want to show a certain message 10000000 times, loops woudld make this simple and painless. 

## Things I want to know more about

*CLASS NOTES*
- Data Type // Data Structure **special type of object**
- A collection or list of elements -> [[1, 2, 3, 4,]], [[5, 6, 7]]
  - Can be mixed types of elements -> store strings, booleans, numbers, and other array

  **JS** 
  //* Anatomy of an array
               <!-- 0    1    2      3 --> --> (EXAMPLE)
let myArray = ['hello', 4, true, [1,2,3]];
let myString = myArray[0];
let myNum = myArray[1];
let myBoolean = myArray[2];
let myNestedArray = myArray[3]; => [1, 2, 3];
let myNestedNum = myArray[3][2]; === let myNestedNum = myNestedArray[1];

- You don't have to predetermine the size of the array
- Ever element has a position in the array -> called it's index!
  - Index is Zero based (starts at 0 ALWAYS)

- Array's have built iin methods
  - `.push()` - allows us to add to our array's 
 - `.pop()` - allows use to remove the LAST element of our array
      - `.push()` and `.pop()` make arrays First In Last oUT (FILO)

- Array property 
  - `.length` - tells you how many element live in your array (different from index) 
        - EX: so above example answer would be 4 because it starts a zero!

Replit Example:

`use strict`

let nums = [1, 2, 3, 4];
console.log(nums);

let mixedArray = ['hello' , 1, true, [1, 2, 3]]

## Loops 

### For loops
  - Good for looping/iterating and doing something a specific number of times
  - Goof for looping through arrays (arrays have length so you can specify how many times you want to flow through the arrays)

  `` js
   <!-- Anatomy of a for loop -->
for (starting value; conditional; increment) {
  <!-- write code here until conditional is no longer true -->
}

<!-- example for loop to print contents of an array-->
for (let i = o; i < myArray.length; i++) {

}
(ex: how to read above: let i equal zero while i is less than four, while increasing amount by 2)