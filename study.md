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
Is this correct?: A method is a function that is a property of an object.  Methods can be written as either:
let obj = {
  age: function(param1) {
    code statements;
  };
};

or

obj.age(param1) {
  code statements;
};

Do both of the above refer to the same method?  Are there any other ways to write a method?




```

Are there any nagging questions related to functions that you have?

```md
let myFunction = function(param1) {
  code;
};
Is this what a function literal is? Because it has an assignment operator, does that make it a function literal instead of a function (such as obj.function() {} )?



Is this how callback functions work?

function myFunction() {} // a function is declared
function callbackFunction(param1, callback) {} // a callback function is declared.  Do you actually write "callback" as the parameter each time you use a callback function?
callbackFunction(param1, myFunction) {} // when the callback function is called, does the name of the  function to be called back replace the parameter "callback" in callbackFunction?

```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md

I'm happy with the progress I've made, I obviously know a lot more than I did a week ago.  Though learning javascript can be very frustrating, it is very rewarding when a concept 'clicks' and I understand it.  I really want to fully understand why each part of the language does what it does.  I know that you guys have said that often being a developer means looking stuff up and copy/pasting it, but I would feel much better if I can avoid doing that as much as possible.  I like learning spoken languages, and really understanding what each part of the language means and does.  The same goes for javascript, but I fear that we're moving so fast that I don't have time to fully grasp the fundamentals.  You can't write words and sentences in a spoken language if you don't know the alphabet, and similarly I find it hard to write code if I dont fully understand the basics.

When we do code-alongs or demos, I can mostly figure out what the code is doing by looking at it for a bit, and I understand why it does what it does.  When it comes to labs or diagnostics that require me to essentially start writing on a blank slate, however, I really struggle because I don't know how to start.  If I am already working with some code, I can run it and use error messages to figure out what to add or change next.  I could just copy some code from a previous lesson to get me started,  but as I said I'd like to avoid doing that because I don't think it will help me learn.  I think that if we spent more time really learning the definitions (and how to write) all the basic building blocks of the code I wouldn't struggle quite so much.  For example, tonight's homework really helped me because the articles really took the time to explain every part of a function.  Specifically, I found the way this site (http://www.quirksmode.org/js/function.html) explained things to be very informative.  I do understand that this is a bootcamp and we have a lot to cover, so maybe I'll have to learn these things on my own time.  I think that this weekend will help, I plan to do a lot of reading on the fundamentals of javascript.  Really my biggest issue so far is not knowing where to start when writing code from scratch.



```
