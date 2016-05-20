# Functions Study

## Required Readings

These readings are to help familiarize you with the subject matter.

Please read the MDN Glossary entries for [Array](https://developer.mozilla.org/en-US/docs/Glossary/array) and [Object](https://developer.mozilla.org/en-US/docs/Glossary/Object)

As well as the following articles:

-   MDN [function expression](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function) reference
-   JSIS [Callbacks](http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them/)
-   Quirksmode [Functions Basics](http://www.quirksmode.org/js/function.html)
-   JS Webblog [Function Declarations vs. Function Expressions](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/)
-   MDN [Return](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return)

There is no requirement to follow any links from these pages.

## Share Your Understanding

After doing all the required readings please tell us anything you were confused about.

```md
I've never understood "return" unless youre just trying to print a message in which case why don't you just console.log().  I see it as just a different location where to send your end product. If a function calculates something then it should spit out that value that was calculated- so whats the difference between:

let coolFunction = function (par){
do this
}
Then call it later, setting it to a variable
variable = coolFunction(parameter);

compared to

let coolFunction = function (par) {
do this
variable = result after doing this
return variable
}

coolFunction(parameter); // sets a variable equal to the result

Then calling it, you dont need to set variable equal to something, there's automatically a variable = the result, you dont need to set a variable to store the value.

Is that correct?

```

Are there any nagging questions relating to functions that you have?

```md
How can you change the value of a global variable from the inside of a function? and have that new value available globally?
```

Thus far how are you feeling about your progress as a developer, please give
an extensive answer?

```md
I am pretty confident in my programming abilities, I just know there's alot of functions
available that I am not using to make my code more efficient. Such as using .forEach
instead of looping through.
```
