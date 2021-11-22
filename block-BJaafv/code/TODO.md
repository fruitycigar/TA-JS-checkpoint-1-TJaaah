1. What is the difference between the two `sum` function given below?

```js
// first
function sum(a, b) {
  return a + b;
}

// second
function sum(a, b) {
  console.log(a + b);
}
```
One of them merely returns the value whereas the other logs (i.e. prints) the value on the console.

2. If we store the returned value of both functions above in variable `first` and `second` what will be the value of `first` and `second`.

The value of `first` will be the sum of a and b in number form.
The value of `second` will be undefined.

3. What will be the output when you call above `sum` function (first) with three parameter like `sum(12, 24, 35)`. Explain why?

?????

4. Can you store the first `sum` function in a variable named `add`. If yes why? If no why?

No. `add` is a keyword in JavaScript that refers to a different method. It will have to take a different name.

5. Declare a function named `sayHello` the accepts a parameter `name` and returns the name like `Hello Arya`.

function sayHello(name) {
  return `Hello ${name.`};
}

6. What will be the output of the function below and why?

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

showMessage();
```

'Hello, John'

7. What will be the output for `Output1` `Output2` and `Output3` in the code below.

```js
let userName = 'John';

function showMessage() {
  let message = 'Hello, ' + userName;
  return message;
}

alert(userName); // John

showMessage(); // 'Hello, John'

alert(userName); // John
```

8. What is a Anonymous Function give example of three functions.

An anonymous function is one in which the function does not have a name.

eg. let what = function () {
  return `What`;
}
eg. let addition = function () {
  return 2 + 45;
}
eg. let show = function () {
  console.log(`I am okay.`);
}

9. Can function declaration be a Anonymous Function? Explain.

Of course. Declaring a function does not mean it should always have a name. It can be stored within a variable and called later.

10. Give 5 example of good naming convention for defining a function. You can read the details below to do that.

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

1. showResults
2. getAge
3. calcDist
4. checkGender
5. createName
