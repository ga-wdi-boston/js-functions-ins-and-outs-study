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
***********************************
in this code :

function counter() {
  for (var count = 1; ; count++) {  // infinite loop
    console.log(count + "A"); // until 5
      if (count === 5) {
        return;
      }
      console.log(count + "B");  // until 4
    }
  console.log(count + "C");  // never appears
}

counter();

when do we use a break statement and when do we use a return statement?
```
***********************************

***********************************
in this code,
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
***********************************
I'm not sure why 3 isn't returned and 8 is returned.   It looks like the foo function is called and the bar function would return 3 because bar is originally declared to return 3 with bar being called right after it.  I'm reading about this "hoisting" stuff now.. I hope it explained in class today.


Are there any nagging questions relating to functions that you have?

```md
Nothing nagging.  Questions just come up as I'm exposed to new code.  I do my best to try to get them
answered via teachers or my squad as soon as I can.  I feel like programming is study that builds upon itself and you want to make sure you "get" a topic because it will be the foundation to the next set of learning.

Thus far how are you feeling about your progress as a developer, please give
an extensive answer?

```md
Feeling four fingers out of five. I understood everything yesterday in the class work ( objects and
prototypes) and I am trying to be shameless about asking questions about things I don't understand.  I've found that by asking questions, I'm solving a lot of my problems and learning more about the
workflow a a developer.
```
