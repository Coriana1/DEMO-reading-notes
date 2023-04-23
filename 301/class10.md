# Understanding the JavaScript Call Stack
1. What is a ‘call’?
  - A function method that allows you to invoke a function and specify the context of the "this" keyword, as well as any arguments that the function should receive.
2. How many ‘calls’ can happen at once?
  - 1 call at a time on a single-threaded JS runtime
3. What does LIFO mean?
  - Last In, First Out - where the last item added to the stack is the first item to be removed
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
  -  function functionA() {
  console.log("Entering functionA");
  functionB();
  console.log("Leaving functionA");
}
function functionB() {
  console.log("Entering functionB");
  functionC();
  console.log("Leaving functionB");
}

function functionC() {
  console.log("Entering functionC");
  console.log("Leaving functionC");
}

functionA();
5. What causes a Stack Overflow?
  - When the call stack of a program exceeds its maximum size - recursive funsctions, excessive function calls, insufficient stack space. 
## JavaScript error messages
1. What is a ‘reference error’?
  -  Type of error in JavaScript that occurs when you try to use a variable that has not been declared or is not in scope.
2. What is a ‘syntax error’?
  - Error in JavaScript that occurs when the code violates the syntax rules of the language.
3. What is a ‘range error’?
  - Type of error in JavaScript that occurs when a value is not within an expected range or set of values.
4. What is a ‘type error’?
  - Type of error in JavaScript that occurs when you try to perform an operation on a value of the wrong type.
5. What is a breakpoint?
  - Point in your code where the debugger will pause execution and allow you to inspect the current state of your program.
6. What does the word ‘debugger’ do in your code?
  - Set breakpoints at specific points in your code, causing the debugger to pause execution when it reaches that point.