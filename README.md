# Process Writeup

## Name: Jianzheng Ruan 
## Course: SEP11 (Conditionals)
## Period: 3rd 
## Concept: learn conditionals and apply inside functions throught coding challenges and projects.
## Introduction: Conditionals is bascially the condition of something when is being compared. In coding conditionals can be used inside a function and often times these functions are being refactored so it can run the different inputs and give back outputs depending on the input which is bascially the parameter and arguments when we define a function. Conditionals work just like huamn languages, if something is not true we don't listen and skip to the next but if something is true than we will follow the steps to finish, the only different in coding is that we have to use symbols like `==` `\\` `&&` to inside the function's condition inorder to return the value inside. Also, in the previous class lessons `{}` wasn't that big of a deal to the codes we write but in this topic , a single `{}` will complete mess up the entir functions. It is important to undersatnd that no matter what input you place the parameter with you won't get the value unless you return it inside the function using `return` and also calling it out of the function outside the function with it's name. Another thing to keep in mind is that once you defined the function you can call it anywhere in the code but you can't call the function before the function is being defined.

## Mainly elements in Conditionals and tinker in Jsbin. (Commonly used ones through out the conditonal lessons)
### Boolean values : only return "true or false" depending on the values
### `If` statements : use to make decisions in code, and will tell Java to excute the condition inside `{}`.
```js
function jz (myCondition) {
  if (myCondition) {
    return "It was true! ";
  }
  return "It was false! ";
}
 
jz(true); // "It was true! "
jz(false); // " It was false! "
```
### `==` operator : compare two values and if they are equal return `true`, if they don't equal turn `false`.
```js
function compare(number) {
  if (number == 10) {
    return "Equal";
  }
  return "Not Equal";
}
compare
