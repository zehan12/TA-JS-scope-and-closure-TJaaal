Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT 51
var numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
console.log(numA + numB); //OUTPUT numA is not defined
let numA = 21,
  numB = 30;
```

Find the output of the code snippets below:

```js
let numA = 21,
  numB = 30;
console.log(numA + numB); //OUTPUT 51
```

Find the output of the code snippets below:

```js
console.log(sayHello()); // OUTPUT "Hello"
function sayHello() {
  console.log("Hey");
}
function sayHello() {
  console.log("Hello");
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT "Tyrion"
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT username is not defined
let username = "Tyrion";
function sayHello() {
  console.log(username);
}
```

Find the output of the code snippets below:

```js
let username = "Tyrion";
sayHello(); // OUTPUT sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT sayHello is not defined
let username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
sayHello(); // OUTPUT sayHello is not defined
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
sayHello(); // OUTPUT sayHello is not defined
let sayHello = () => {
  console.log(username);
};
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  var username = "John";
};
sayHello(); // OUTPUT undefined
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  var username = "John";
  console.log(username);
};
sayHello(); // OUTPUT "John"
```

Find the output of the code snippets below:

```js
var username = "Tyrion";
let sayHello = () => {
  console.log(username);
  let username = "John";
};
sayHello(); // OUTPUT username cannot access before initializing
```