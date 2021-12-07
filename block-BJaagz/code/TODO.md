1. Implement `forEach` array method using Array.reduce

- `forEach` accepts two parameter array and callback
- It does not return anything
- It should work exactly like array `forEach` method

```js
function forEach( array , name , i , arr ) {
   array.reduce(acc,cv,i,arr)=>{
     console.log(acc+cv,i,arr);
     return acc;
   }
}

forEach(['Sam', 'Jon', 'Arya'], (name, i, arr) =>
  console.log(name + name, i, arr)
);
```

2. Implement `map` array method using Array.reduce

- `map` accepts two parameter array and callback
- It returns same size of array
- It should work exactly like array `map` method

```js
function map(array) {
  // Your code goes here
  let result = array.reduce((acc,cv,index)=>{
       acc[index] = cv + cv ;
    return acc;
  },[ ])
  return result;
}

  // Your code goes here
function map(array) {
  let result = array.reduce((acc,cv,index)=>{
       acc.push(cv);
    return acc;
  },[ ])
  return result;
}


map(['Sam', 'Jon', 'Arya'], (name) => name + name); // ['SamSam', 'JonJon', 'AryaArya']
```

3. Implement `filter` array method using Array.reduce

- `filter` accepts two parameter array and callback
- It returns same size or smaller array
- It should work exactly like array `filter` method

```js
function filter(array) {
  // Your code goes here
  let result = array.reduce((acc,cv,index)=>{
    acc[index] = cv.startsWith('S');
    return acc;
  },[])
  return result
}

filter(['Sam', 'Jon', 'Arya'], (name) =>
  name.startsWith('S')
); // ['Sam']
```
