# arrow-functions
Arrow function is a  a more concise syntax for writing function expressions. It utilizes a new token, =>

Two factors influenced the introduction of arrow functions: the need for shorter functions and the behavior of the this keyword.

Arrow functions were introduced due to a need to write shorter functions.

Before arrow functions, every new function defined its own this value based on how the function was called
and this proved to be less than ideal with an object-oriented style of programming and something had to be done on the "this" keyword.

An arrow function does not have its own this keyword.

Arrow functions can have either a block or a straight statement.
If there are many arguements involved,then a block is ideal,but if it only involves one arguement then a straight simple arrow function is needed.

// ES6
let selected = allJobs.filter(job => job.isSelected());
