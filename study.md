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
I am confused about nested callbacks and the example given in the article about return:

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

I understand that something about the way bar() is defined both times causes JavaScript to read it before the return but I'm not sure what that thing is.
```

Are there any nagging questions related to functions that you have?

```md
What is the difference between the various ways of declaring functions? we touched on the
difference between the arrow notation and typing out a function literal but there are
apparently noteworthy differences between

function aFunction() {
  return true;
}

and

const aFunction = function () {
  return true;
};

I would think (assuming I do not have a syntax error somewhere in there) that these should
behave identically and yet one of the blog posts seems to imply it does not.
```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md
I feel like, although a lot of the stuff we are covering right now is stuff I had used
before and know how to type out or copy and use, I am learning how it actually works,
which is restroactively making me realize why certain things I was working on were actually
broken and why the fixes worked.
```
