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
Anonymous funtions seem intriguing and as i read more they seemed to make more
sense. But they do have a bit of a learning curve to use from what I see. I
really found this block of code to be useful as an example:

​function getInput (options, callback) {
    allUserData.push (options);
    callback (options);

I see that I can pass the one function an argument and another function, and then
use the argument with the function that was passed inside of the fucntion they
were passed to. This is very very helpful.
Once we started adding tohis(this) into the mix things get a little harder to
parse for me, but I feel like some hands on with code using these techniques -
i.e. breaking some stuff, will help me get these concepts a lot better.

```

Are there any nagging questions related to functions that you have?

```md
I had a hard time for a while with some of the concepts of passing around
variable to functions depending on scope, but the recent exercises have really
helped the concepts to make logical sense to me. Object oriented languages and
abstraction in general are comfortable concepts for me so going over the basics
is pretty easy. The questions I have are well beyond some of what we are covering.
Most explicitly, I want to see how this starts working once we add in the back end.
Programming for a single client isn't that tricky, but I found once we had a client
and a server passing stuff around it got a lot more complicated so i am looking
forward to getting to this stuff most of all.
```

Thus far, how are you feeling about your progress as a developer? Please give an
extensive answer.

```md
I am happy to say that after some good sleep and solid meals, I am feeling confident.
I had some issues with some of the syntax with passing around stuff from array to object
and back again. But I played around a good bit this morning and got some code working.
I even get the boggle concept using multiple arrays. 4 arrays of a length of 4 -
each array represent a row, with each new array "stacking" on top of the next.
Using coordinates, the first number is the array itself (the row), the second
coordinate is the index of the array chosen. I even figured out a way to just
break an array down. Since we know the size of the grid we want its easy to just
read the array starting at a specific point and ending at a speicific
point( 0-3, 4-7, 8-11, etc.) and just make new arrays. This itself would be a
function(something like creatBoggleBoard)....but i know you get this. What I am
attemptint to illustrate is I am comfortable enough now that I can even do a lot
of this logic in my head. In fact, as I slept last night, these concepts were
what I fell asleep thinking about and what I woke up thinking about. In other
words, I am literally starting to dream in code now.

My biggest concern is one of time management. I was never good at studying, and
usually just passed in school with little effort. I am forcing myself to work
outside of class and think about these concepts as much as possible. I took
Saturday as an entire me day so that I could hit this stuff HARD today.

Between the excellent instruction, great classmates, and a strong foundation
already, i am 100% confident I will be where I need to be at the end. Perhaps a
worn out... but hard anything worth anyting ain't easy....

```
