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
<!--
1.self invoking function expression

https://javascriptweblog.wordpress.com/2010/07/06/function-declarations-vs-function-expressions/
//**Simulated processing sequence for Question 2**
function foo(){
    //a declaration for each function expression
    var bar = undefined;
    var bar = undefined;
    //first Function Expression is executed
    bar = function() {
        return 3;
    };
    // Function created by first Function Expression is invoked
    return bar();
    // second Function Expression unreachable
}
alert(foo()); //3
2.Why is the second function expression unreachable? I understand that a function will exit after it gives a return value but how is the above to return the first and not the second? How is true determined to return the first return statement?-->
```

Are there any nagging questions related to functions that you have?

```md
<!-- Answered in q1 && 3-->
```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md
<!-- I have a clear understanding about git status, add, commit, push and pull a request in github.
I can identify an array and an object, and I also know how to access them (Array- Through index number || with methods; and objects through the key.
The real confusion is when it comes to functions... for example functions that create an array or an object... the past two days, I have felt clueless about functions... I am going over additional readings and sites,after doing the homework; still at the time of producing a function I can't go beyond let or const x = function y () {};
I know the parts of a for loop (initialization, condition, increment)statement... but can't produce one. I understand a function has parameters and those are then replaced with arguments... basically I can't create a function on my own...

Yes, I am learning and I feel I can identify many parts in code... producing code is the challenge so far...) -->
```
