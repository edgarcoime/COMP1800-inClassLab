# Questions to answer

## Q1: Is the keyword "fixes" the only way to auto-close an issue from a PR (pull request). Is there other keywords that can accomplish the same thing?

Fixes is not the only way to auto-close and issue or link an issue in github. Some of the keywords includes:
*close
*closed
*fix
*fixed
*resolve

## Q2: Do you have to create a new PR EVERYTIME you want to close an issue,or is it possible to close multiple issues within a single PR? If so, how?

No you do not have to create a new PR everytime you want to close an issue. There are keywords that you can use to close multiple issues such as:
*closes
*fixes
*resolves

## Q3: Provide an example of using map that is different from the one I have done.Your example must use map both as a named function declaration and with ananonymous function. 

The map function creates a new array by calling an inputted function or method on every element in the called array. Like the example below.

```javascript
// example 1
var numbers = [4, 9, 16, 25];
// Normal named function declaration
function myFunction() {
  x = document.getElementById("demo")
  x.innerHTML = numbers.map(Math.sqrt);
}
```

Functions are objects in JavaScript and because of this functions can take other functions as arguments. Any function that is passed as an argument is called a __callback function__

```javascript
// example 2

let numbers = [1 , 4, 9, 16, 25]
let squareRoots = numbers.map(function(num) {
    return Math.sqrt(num)
})

```
