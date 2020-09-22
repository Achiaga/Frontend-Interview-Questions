# JS Questions

### 1. Difference Map, Reduce and Filter
>
##### Short Answer:
>
>
>
>
>
>
>
>
>
>
##### Complete Answer:
>
> [Link to answer 1](https://codeburst.io/array-methods-explained-filter-vs-map-vs-reduce-vs-foreach-ea3127c6d319)
>
> [Link to answer 2](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d)

<br />

### 2. What is Debbuging on Js
>
##### Short Answer:
>
> Is the process of detecting and removing of existing and potential errors.
>
> Ex: Chrome Inspector. Tricks: debugger, console.log,
>
##### Complete Answer:
>
> [Link to answer 1](https://raygun.com/learn/javascript-debugging-tips)
>

<br />

### 3. Do you know what is Webpack?
>
##### Short Answer:
>
> A static module bundler for modern javascript applications. It builds a dephency graph which maps every module of your project needs and it generates one or more bundles.
>
##### Complete Answer:
>
> [Link to answer 1](https://webpack.js.org/concepts/)
>

<br />

### 4. What is the difference between Javascript vs Vanilla Javascript?
>
##### Short Answer:
>
> No difference at all. Vanilla it is just a way to refer to native Javascript. It is a term to contrast between pure javascript and libraries/frameworks.
>
##### Complete Answer:
>
> [Link to answer 1](https://stackoverflow.com/questions/20435653/what-is-vanillajs)
>

<br />

### 5. Do you know Babel and what is difference between ES2015+ and Js?
>
##### Short Answer:
>
> Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. 
>
##### Complete Answer:
>
> [Link to answer 1](https://babeljs.io/docs/en/)
>

<br />

### 6. What is the difference between Async/Await and Promises?
>
##### Short Answer:
>
> Defintion: It is an object that may produce a single value some time in the future. It use callbacks to handle the fullfilled value or rejection. A promise is an > object which can be returned synchronously from an asynchronous function.
>
> Promise: Only the promise chain itself is asyn. Sync code can be handled in the same callback. Then / Catch / Finally. For simple cases.
>
> Async: The entire wrapper function is async. Sync work needs to be moved out of the callback. Try / Chain / Finally. For Complex cases. (nicer syntax)
>
##### Complete Answer:
>
> [Link to answer 1](https://medium.com/better-programming/should-i-use-promises-or-async-await-126ab5c98789#:~:text=await%20is%20always%20for%20a,executed%20when%20the%20promise%20resolves.)
>
> [Link to answer 2](https://levelup.gitconnected.com/async-await-vs-promises-4fe98d11038f)
>
> This is not an answer but I think it is a nice article to read about async
> [Related Link](https://medium.com/better-programming/is-javascript-synchronous-or-asynchronous-what-the-hell-is-a-promise-7aa9dd8f3bfb)
>


<br />

### 7. What are callbacks?
>
##### Short Answer:
>
> So a function that is passed to another function as a parameter is a callback function.
>
> Callbacks make sure that a function is not going to run before a task is completed but will run right after the task has completed. It helps us develop asynchronous JavaScript code and keeps us safe from problems and errors.
>
>
##### Complete Answer:
>
> [Link to answer 1](https://www.freecodecamp.org/news/javascript-callback-functions-what-are-callbacks-in-js-and-how-to-use-them/)
>


<br />

### 8. What is an Anonymous Function?
>
##### Short Answer:
>
> We can define a function directly inside another function, instead of calling it. It will look like this:
>
> ```js
> setTimeout(function() {  
>    console.log("This message is shown after 3 seconds");
> }, 3000);
> ```
>
> The callback function here has no name and a function definition without a name in JavaScript is called as an “anonymous function”. 
>
##### Complete Answer:
>
> [Link to answer 1](https://www.freecodecamp.org/news/javascript-callback-functions-what-are-callbacks-in-js-and-how-to-use-them/)
>


