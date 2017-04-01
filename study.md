# JavaScript: Functions Ins and Outs Study

Use your favorite search engine and the provided readings to research and
respond to the following questions.

In your responses, be sure to cite any relevant sources you consulted in your
search. We ask you to write responses in your own words in order to see how you
process what you've read. Please do not respond with direct quotes from source
material. Instead, digest what you've read and repeat it in your own voice.

## Required Readings

-   [Object - Glossary | MDN](https://developer.mozilla.org/en-US/docs/Glossary/Object)
-   [Array - Glossary | MDN](https://developer.mozilla.org/en-US/docs/Glossary/Array)
-   [function expression - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/function)
-   [return - JavaScript | MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/return)
-   [Understand JavaScript Callback Functions and Use Them](http://javascriptissexy.com/understand-javascript-callback-functions-and-use-them)
-   [JavaScript - Functions](http://www.quirksmode.org/js/function.html)
-   [Function Declarations vs. Function Expressions](https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions)

## Share Your Understanding

After reading all of the required readings, please tell us anything that you
were confused about.

```md
In the javascript is sexy article about callback functions:

I'm confused about how call and apply are working. I understand that we are using them to make t-his be invoked on its original parent object and not in its current scope. I just haven't been able to wrap my head around what the process thats happening is. I am also not quite sure what the arguments object is and why we need it when we use call.

In regards to the mozilla definitions of object and array:

does an array inherit any methods from the pre existing Object? do objects and arrays share any predefined methods?

```

Are there any nagging questions related to functions that you have?

I have some questions about closures from reading:
http://javascriptissexy.com/understand-javascript-closures-with-ease/

particulary regarding the information under the headings:

-Closures have access to the outer function’s variable even after the outer function returns-:

I dont understand why the closure would run after its parent function returns.

-Closures store references to the outer function’s variables-:

I dont understand quite whats happening in the snippet under this heading. I'm not sure if its important that I understand it right now.




```md
What is function hoisting, hoisting in general. Do i need to know?

I think I need to know. I remember something being said about hoisting being a little less important to think about in es6 using const and let.

I referenced the javascriptweblog article for this question and googled it and looked at stack overflow

a function declaration along with its body gets hoisted to the top of its scope when the code runs. something like:

function bar (foo) {
  console.log(foo)
}

a function expression:

var foo = function (baz) {
  console.log(baz)
}

 Also gets hoisted to the top of its scope, but only the left hand variable declaration.
 only var foo would get hoisted. Then foo would be reassigned to the function in the place where the code was written.

 I understand how hoisting works with var here. is it the same when using const or let?


```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md
  I did tutorials online for about 3 months before WDI. We've already surpassed what I learned on my own after our first week. I'm happy about that, I think that confirms that WDI was the right choice for me. I'm looking forward to learning at this pace for another 11 weeks.

  I'm not sure if I'm able to judge my progress all that well. I know I've learned a lot so far. I worked on Javascript, HTML and CSS everyday for 3 months before WDI started and I feel like that made me a little more ready. I was trying to give myself a headstart. We've already gotten into material that is very challenging for me, that I have to struggle to grasp. That tells me that ongoing learning is the most important thing. Everday of WDI I've realized how much more there is that I dont know yet. I hope I don't let myself get too discouraged by that.

  Right now I feel really excited about my progress so far. I don't feel like I'm able to quantify how much more I need to learn to be useful to a company at this point. That uncertainity concerns me a bit. I'm glad that the Javascript concepts we've gone over so far have been challenging for me and that I've had a lot of 'aha' moments.

  I'm starting to really enjoy the hard challenges in class that are beyond me. I'm happy about that change in attitude.


```
