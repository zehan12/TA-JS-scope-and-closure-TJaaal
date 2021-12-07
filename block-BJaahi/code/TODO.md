For the given code below:

- re-write the code in ways that system will understand

For Example:

1.

```js
var username = 'Arya';
let brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Declaration Phase
var username = undefined;
let brothers;

function sayHello(name) {
  return `Hello ${name}`;
}

let message;
var nextMessage = undefined;

// Execution Phase

username = 'Arya';
brothers = ['John', 'Ryan', 'Bran'];

console.log(username, brothers[0]);

message = sayHello(username);
nextMessage = sayHello('Test');
```

2.

```js
console.log(username, numbers);

var username = 'Arya';
let number = 21;

function sayHello(name) {
  return `Hello ${name}`;
}

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here

//Declaration Phase

var  username = undefined;
let numbers;

function sayHello(name) {
  return `Hello ${name}`
}

let message;
var nextMessage = undefined;

//Execution Phase

console.log(username, numbers);

username = "Arya";
numbers = 21;

message = sayHello(username);
nextMessage = sayHello("Test");


```

3.

```js
console.log(username, numbers);
let username = 'Arya';
let number = 21;

let sayHello = function (name) {
  return `Hello ${name}`;
};

let message = sayHello(username);
var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here

// Declaration Phase

let username;
let number;

let sayHello;

let message;

var nextMessage;

//Execution Phase

console,log(username, numbers);
username = "Arya";
number = 21;

message = sayHello(username);
nextMessage = sayHello("Test");
```

4.

```js
let username = 'Arya';
console.log(username, numbers);

let number = 21;
let message = sayHello(username);

let sayHello = function (name) {
  return `Hello ${name}`;
};

var nextMessage = sayHello('Test');
```

<!-- Answer -->

```js
// Your code goes here

// Declaration Phase

let username;

let number;
let message;

let sayHello;

var nextMessage = undefined;

// Execution Phase

username = "Arya";
console.log(username, numbers);

number = 21;
message = sayHello(username);

sayHello = function (name) {
  return `Hello ${name}`;
};

nextMessage = sayHello("Test");
```

5.

```js
console.log(name);
console.log(age);
var name = 'Lydia';
let age = 21;
```

<!-- Answer -->

```js
// Your code goes here

// Decarlation Phase

var name = undefined;
let age;

// Execution Phase

console.log(name);
console.log(age);
var name = "Lydia";
age = 21;

```

6.

```js
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

sayHi();
```

<!-- Answer -->

```js
// Your code goes here

// Declartion Phase 

sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

// Execution Phase

sayHi() = 
  console.log(name); //"Lydia"
  console.log(age);  //"undefined"

```

7.

```js
sayHi();
function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}
```

<!-- Answer -->

```js
// Your code goes here

// Decarlation Phase

sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
}

// Execution Phase

sayHi =
  console.log(name); //"Lydia"
  console.log(age);  //"undefined"

```

8.

```js
sayHi();
let sayHi = function sayHi(name) {
  console.log(name);
  console.log(age);
  var name = 'Lydia';
  let age = 21;
};
```

<!-- Answer -->

```js
// Your code goes here

// Decarlation Phase

let sayHi;

// Execution Phase

sayHi = Reference Error;

```

9.

```js
let num1 = 21;
console.log(sum);
var sum = num1 + num2;
let num2 = 30;
```

<!-- Answer -->

```js
// Your code goes here

// Declartion Phase

let num1;

var sum = undefined;
let num2;

// Execution Phase

num1 = 21;
console.log(sum)//num2 is not defined;
```

10.

```js
var num1 = 21;

let sum2 = addAgain(num1, num2, 4, 5, 6);

let add = (a, b, c, d, e) => {
  return a + b + c + d + e;
};
function addAgian(a, b) {
  return a + b;
}
let num2 = 200;

let sum = add(num1, num2, 4, 5, 6);
```

<!-- Answer -->

```js
// Your code goes here

// Declartion Phase

var num1 = 21;

let sum2;

let add;

addAgain = function addAgian(a, b) {
  return a + b;
}

let num2;

let sum;

// Execution Phase

num1 = 21;

sum2 = //addAgain not defined;

```

11.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

let add = (a, b) => {
  return a + b;
};
```

<!-- Answer -->

```js
// Your code goes here

// Declartion Phase

test = function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum;

let add;


// Execution Phase

sum = test(100) //add is not defined;

```

12.

```js
function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum = test(100);

function add(a, b) {
  return a + b;
}
```

<!-- Answer -->

```js
// Your code goes here

// Declartion Phase

test = function test(a) {
  let num1 = 21;
  return add(a, num1);
}

let sum;

add = function add(a, b) {
  return a + b;
}

// Execution Phase

sum = test(100) //212

```
