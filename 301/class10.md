# In memory storage

### Summary of Why Reading are Relevant

## Readings
### [Understanding the JavaScript Call Stack]([HTML](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4))
1. What is a ‘call’?
  - When a function is invoked
2. How many ‘calls’ can happen at once?
  - one
3. What does LIFO mean?
  - Last in first out
4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
~~~ js
function firstFunction(){
  throw new Error('Stack Trace Error');
}

function secondFunction(){
  firstFunction();
}

function thirdFunction(){
  secondFunction();
}

thirdFunction();
~~~
~~~
Uncaught Error: Stack Trace Error
  at firstFunction ( <anonymous>:2:7)
  at secondFunction (<anonymous>:7:1)
  at thirdFunction (<anonymous>:11:1)
  at <anonymous>:14:1
~~~
5. What causes a Stack Overflow?
  - a function that calls itself without an exit point

### [JavaScript error messages]([HTML](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c))
1. What is a ‘reference error’?
  - When a variable that has not been declared is called
2. What is a ‘syntax error’?
  - when an action cannot be performed due to invalid syntax
3. What is a ‘range error’?
  - when you try to use length on a variale with an invalid length
4. What is a ‘type error’?
  - when types of variables being used are incompatible
5. What is a breakpoint?
  - inserting concole.log() or a debugger statement to evaluate what has happened at that point in your code
6. What does the word ‘debugger’ do in your code?
  - it pauses the debugger


### Things I want to know more about:
  -

open projects/courses/code-301/seattle-code-301d96/class-##/DISCUSSION.mdUnderstanding the JavaScript Call Stack
