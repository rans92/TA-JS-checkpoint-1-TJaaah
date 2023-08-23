1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}
// In this sum function return is used to provide a value back to the caller and terminate the execution of a function.

// second
function sum(a, b) {
  console.log(a + b);
}
//In this sum function only print value in console. Console.log() is used for printing information to the console during program execution,
```

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

 <!--  Ans : In first sum function returned value can be store in variable. But in second sum function we can't store returned value. -->

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?
 
 <!-- Ans: If we call sum function with three parameters it return only sum of first two parameters cause our function is define only with two paramters. -->

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

<!-- Yes, we store the first 'sum' function in a variable named 'add' cause this function is with return keyword which provide value back to caller. --> 

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

```js
function sayHello(name) {
  return 'Hello ' + name ;
}
```

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```
<!-- showMessage funtion return 'Hello, John' userName globally assigned as John and message is assigned as 'Hello, ' + userName . When showMessage function is called then it return message. -->

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // Output 1 -- It alerts "John" in web page.

showMessage(); // Output 2 -- It returns "Hello, John ".

alert(userName); // Output 3 -- It alerts "John" in web page.
```

8. What is a Anonymous Function give example of three functions.
<!-- An anonymous function is a function without a function name. Only function expressions can be anonymous, it is a function that does not have any name associated with it. 
eample:
const sum = function(a, b) {
  return a + b
  }
  const square = function(num) {
  return num * num
  }
  const findDifference = function(numA , numB ) {
  return numA - numB
  }
  -->

9. Can function declaration be a Anonymous Function? Explain
<!-- No, an anonymous function is a function without a function name. Function declarations must have a name -->

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.
<!-- 5 good example of funtion name are :-
function findDifference(numA, numB){
  return numA - numB;
}
 function sum(a, b){
  return a + b 
  }
  -->

```md
Functions are actions. So their name is usually a verb. It should be brief, as accurate as possible and describe what the function does, so that someone reading the code gets an indication of what the function does.

It is a widespread practice to start a function with a verbal prefix which vaguely describes the action. There must be an agreement within the team on the meaning of the prefixes.

For instance, functions that start with "show" usually show something.

Function starting with…

"get…" – return a value,
"calc…" – calculate something,
"create…" – create something,
"check…" – check something and return a boolean, etc.
```
