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
Interrupting a function by return; - when the code get executed to the "return;" what will trigger it to go back to print out "B" ? Also I would think that the result will not get any numbers with B then when return; gets in.

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

// Output:
// 1A
// 1B
// 2A
// 2B
// 3A
// 3B
// 4A
// 4B
// 5A

```

Are there any nagging questions related to functions that you have?

```md
When you get an example of named function expression - I don't understand how come it doesn't follow the rule of if (n <= 1) {return 1;} else {return n * factorial(n - 1);}
This is the confusing part about JavaScript.

var math = {
  'factorial': function factorial(n) {
    if (n <= 1)
      return 1;
      return n * factorial(n - 1);
  }
};
```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md
For me to start to code in JavaScript it's super important - more than any other related languages. I have basics of JavaScript for while but took GA to hear finally foundations and logic of lines of codes that is behind. Don't want to only hack but also code from scratch. Also, the asnwers to "why this" "why that" is the most to put together puzzles of JavaScript concepts that language offers. But the pace is very advanced. I don't see a problem to understand the concept of entire "case study" in 15 - 20 minuts if I get an individual attention after the theory. It's a great idea of students helping each other if it works but unfortunatelly our team isn't good enough to know and share around. The result is that we don't work much together.  So I have a little space to talk about problems with my code and I see I am not growing rather stuck with more and more problems. In some point today I had probably finished 70% of assignment in a cool way but because I couldn't finish that 30% I showed it to one student from other group who was done with the assignment and she pushed me to rewrite my code the way how she knows that it will work because she didn't know my way. Now we have both the same code - hers and I don't see I am growing because her thinking isn't mine. I have heard that some GA classes have 15 students - definitelly our 28 students is too big and I don't see any advantage of that number. Also I don't think that node.js can help If you don't know how to structure the code. Forgetting closing {} can also happend when not knowing how the code goes... where the block of code should close.
```
