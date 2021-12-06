1. Convert the function below into different forms of function expression.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}

// Your code goes here
let percentage = function(marks, total){
  return (marks * 100)/ total;
}
```

2. Write Function Declaration or Function Expression next to the function.

```js
function percentage(marks, total) {
  return (marks * 100) / total;
}
// Your answer

Function Declaration
```

```js
let percentage = function percentage(marks, total) {
  return (marks * 100) / total;
};

Function Experession 
```

```js
let percentage = function (marks, total) {
  return (marks * 100) / total;
};

Function Expression
```

```js
let percentage = (marks, total) => {
  return (marks * 100) / total;
};

Function Expression
```

```js
let percentage = (marks, total) => (marks * 100) / total;

Function Expression
```

3. Why is a function definition an expression in JavaScript? Give one example of function expression.

Function expression means store a function defination into a variable is known as function expression.

let sumAll = function ( a, b, c, d ){
  return a + b + c + d ;
}

4. Why is a function call an expression in JavaScript?

function call an expression call the function with function name with call operator ().

5. Write VALID and INVALID next to each example below with the reason.

```js
function add(a, b) {
  return a + b;
}

let five = add(2, 3); // Answer VALID
five = add; // Answer VALID
five = five(10, 11); // Answer VALID
five = function () {
  return 'Hello';
}; // Answer VALID
```

6. What is the difference between function definition and function call? Explain with an example.

function definiton explain step of function in it and whereas function call call the function with the call operator ().

function definition 

function add( x, y){
  return x + y ;
}

function call

add(2,3);


7. What is the similarities between function definition and function call?

there is no similarities between function definition and function call both are different one is step of function and other one is exectue that function

8. Is the code below valid or invalid. Explain with reason.

```js
function hello() {
  console.log('Hello World!');
}

hello.user = 'Sam'; // valid or invalid

//valid
```

9. What is higher order function explain with an example.

higher order function is a function when one function return another function in it and one function take another function as callback function.

```js
let greeting = function(){
  return "hello"
}

function call(callback){
  return callback()
}

call(greeting);

let fun = function(){
  return function(){
    return "say hello"
  }
}
```

10. Explain what is callback function. Why you can pass a function inside a function?

when function pass another function as a callback function as a reference

eg:

```js
let btn = document.querySelector("button");

function toggle(){
   btn.style.backgroundColor = "red";
}

btn.addEventListener('click', toggle);


function firstAction(){
  console.log('first Action')
  setTimeout(secondAction, 2000)
}

function secondAction(){
  console.log('second Action')
}

setTimeout(firstAction, 5000);

```