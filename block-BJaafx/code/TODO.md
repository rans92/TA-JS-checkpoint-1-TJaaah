1. Using loops take 10 inputs from user and find the average of all the numbers.
```js
let sum = 0;
for (i = 1; i <= 10; i++) {
  let input = +prompt(`Enter input${i}`);
  sum += input;
}
let average = sum / 10;
alert(average);

```

2. What will be the output of the code below

```js
let i = 0;
while (i < 3) {
  println('hi');
  i++;
}
```

3. Write a function named `getEvenSum` that accepts a parameter `max`. Return the sum of all even numbers. The value of max should default to 10.
```js
function getEvenSum(max = 10){
  let sum = 0;
  for (let i = 0; i <= max; i = i + 2) {
    sum = sum + i
  }
  return sum;
}
```

4. Write a function named `getOddSum` that accepts a parameter `max`. Return the sum of all odd numbers. The value of max should default to 10.
```js
function getOddSum(max = 10){
  let sum = 0;
  for (let i = 1; i <= max; i = i + 2) {
    sum = sum + i
  }
  return sum;
}
```

5. Write a function named `getProductOfDigits` that accepts a parameter `num`. It returns the product of all the digits in the number.

- If the input value is less than 0 return `not a valid input`
- For example if the input is `123` output should be `6`.


6. What will be the output of the following code below in multiple conditions? Explain with reason?

```js
function check(num) {
  if (num > 5) {
    return 'Bigger than 5';
  }

  if (num < 5) {
    return 'Smaller than 5';
  }

  return num;
}

check(10); // output is 'Bigger than 5'
check(1); // output is 'Smaller than 5'
check(5); // output is 5
```

7. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') return 'You are arya';
  if (name === 'John') return 'You are john';
  return 'Who are you';
}

getOutput('Arya'); // what will be the output - 'You are arya'
getOutput('John'); // what will be the output - 'You are john'
getOutput(); // what will be the output - 'Who are you'
```

8. What will be the output of the following code given below? Explain the reason?

```js
function getOutput(name) {
  if (name === 'Arya') console.log('You are arya');
  if (name === 'John') console.log('You are john');
  return 'Who are you';
}

getOutput('Arya'); // what will be the output - 'You are arya' 'Who are you'
getOutput('John'); // what will be the output - 'You are john' 'Who are you'
getOutput(); // what will be the output - 'Who are you'
```

9. Can a function have multiple return statement? Give one example if possible and explain the reason.
```js
function productPrice() {
let product = prompt("Enter the product ?");
if ( product == "phone") {
return ("price is 8000")
} else if (product == "laptop") {
return ("price is 50000") 
} else if (product == "watch") {
return ("price is 25000") 
} else if (product == "tv") {
return ("price is 45000") 
} else if (product == "tablet"){
return ("price is 35000")
} else 
return ("Enter valid Product Name");
}
```

10. What is the difference between `for` loop and `while` loop. What are the different place you can use them? Explain with example.
<!-- The major difference between for loop and the while loop is that for loop is used when the number of iterations is known, whereas execution is done in the while loop until the statement in the program is proved wrong.
 -->