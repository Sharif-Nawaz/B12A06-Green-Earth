"# Green Earth Project" 
"# b12a6-green-earth-Sharif-Nawaz" 


1) What is the difference between var, let, and const?

..var

Function-scoped (available inside the whole function).
Can be redeclared and updated.
Gets hoisted (declared at top of scope automatically).

..let

Block-scoped (limited to { ... } block).
Cannot be redeclared in the same scope but can be updated.
Introduced in ES6 to avoid var issues.

..const

Block-scoped.
Must be initialized when declared.
Cannot be reassigned, but objects/arrays inside can be modified.




2) What is the difference between map(), forEach(), and filter()?

..map()

Returns a new array with transformed elements.
Example: [1,2,3].map(x => x * 2) → [2,4,6]

..forEach()

Loops through each element but does not return a new array.
Mainly used for side effects (logging, updating external variables).
Example: [1,2,3].forEach(x => console.log(x))

..filter()

Returns a new array with elements that match a condition.
Example: [1,2,3,4].filter(x => x % 2 === 0) → [2,4]





3) What are arrow functions in ES6?

A shorter syntax for writing functions.
Example:
const add = (a, b) => a + b;


4) How does destructuring assignment work in ES6?

A way to unpack values from arrays or objects into variables.

Example (Array):

const [a, b] = [10, 20];
console.log(a); 
console.log(b); 

Example (Object):
const {name, age} = {name: "Sharif", age: 22};
console.log(name);




5) Explain template literals in ES6. How are they different from string concatenation?

Strings written with backticks ( ) instead of quotes.
Allow expression interpolation and multi-line strings.

Example:Strings written with backticks ( ) instead of quotes.

Allow expression interpolation and multi-line strings.

Example:

const name = "Sharif";
const trees = 5;
console.log(`Hello, ${name}! You planted ${trees} trees.`);
