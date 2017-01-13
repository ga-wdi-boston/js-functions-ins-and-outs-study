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
I am confused about nested callbacks and the example given in the article about return:

```js
function foo(){
    function bar() {
        return 3;
    }
    return bar();
    function bar() {
        return 8;
    }
}
alert(foo());
```

I understand that something about the way bar() is defined both times causes JavaScript to read it before the return but I'm not sure what that thing is.
```

Are there any nagging questions relating to functions that you have?

```md
What is the difference between the various ways of declaring functions? we touched on the
difference between the arrow notation and typing out a function literal but there are
apparently noteworthy differences between

```js
function aFunction() {
  return true;
}

AND

const aFunction = function () {
  return true;
};
```
I would think (assuming I do not have a syntax error somewhere in there) that these should
behave identically and yet one of the blog posts seems to imply it does not.
```

Thus far how are you feeling about your progress as a developer, please give
an extensive answer?

```md
I feel like, although a lot of the stuff we are covering right now is stuff I had used
before and know how to type out or copy and use, I am learning how it actually works,
which is restroactively making me realize why certain things I was working on were actually
broken and why the fixes worked.
```
