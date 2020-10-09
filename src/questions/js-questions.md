# JS Questions

### 1. Difference Foreach, Filter, Map, and Reduce
>
##### Short Answer:
>
> **Foreach** takes a callback function and run that callback function on each element of array one by one.
> 
 ```js
 var sample = [1, 2, 3];

 sample.forEach((elem, index) => `${elem} comes at ${index}`)

 /*
 output
 1 comes at 0
 2 comes at 1
 3 comes at 2
 */

```
>
> Basically forEach works as a traditional for loop looping over the array and providing you array elements to do operations on them.


> **Filter:** The main difference between forEach and filter is that forEach just loop over the array and executes the callback but filter executes the callback and check its return value.
>
 ```js
 var sample = [1, 2, 3];

 var result = sample.filter(elem => elem !== 2)

 /* output */
 [1, 3]


```
>
>Basically, if the callback function returns true, the current element will be in the resulting array. If it returns false, it won’t be.


> **Map:** like filter & foreach takes a callback and run it against every element on the array but whats makes it unique is it generate a new array based on your existing array.
>
 ```js
 var sample = [1, 2, 3] // i am never gonna change Boo! Yeah

 let mapped = sample.map(elem => elem * 10)

 /* output */
 [10, 20, 30]

```
>
> Like filter, map also returns an array. The provided callback to map modifies the array elements and save them into the new array upon completion that array get returned as the mapped array.


> **Reduce:** Just like .map(), .reduce() also runs a callback for each element of an array. What’s different here is that reduce passes the result of this callback (the accumulator) from one array element to the other.
>
```js
var pilots = [
  {
    id: 10,
    name: "Poe Dameron",
    years: 14,
  },
  {
    id: 2,
    name: "Temmin 'Snap' Wexley",
    years: 30,
  },
  {
    id: 41,
    name: "Tallissan Lintra",
    years: 16,
  },
  {
    id: 99,
    name: "Ello Asty",
    years: 22,
  }
];

// We need to know the total years of experience of all of them. With .reduce(), it’s pretty straightforward:

const totalYears = pilots.reduce((acc, pilot) => acc + pilot.years, 0);

// output: 82

// Now let’s say I want to find which pilot is the most experienced one. For that, I can use reduce as well:

var mostExpPilot = pilots.reduce(function (oldest, pilot) {
  return (oldest.years || 0) > pilot.years ? oldest : pilot;
}, {});

```
>
> Like filter, map also returns an array. The provided callback to map modifies the array elements and save them into the new array upon completion that array get returned as the mapped array.
>
##### Complete Answer:
>
> [Link to answer 1](https://medium.com/poka-techblog/simplify-your-javascript-use-map-reduce-and-filter-bd02c593cc2d)
>
> [Link to answer 2](https://codeburst.io/array-methods-explained-filter-vs-map-vs-reduce-vs-foreach-ea3127c6d319)

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


<br />

### 9. Rest API
>
##### Short Answer:
>
> API acts as a layer between your application and external service.
>
> REST API (Representational state transfer) is an API that uses HTTP requests for communication with web services and must comply with certain constraints.
>
> CRUD is a programming concept denoting four basic actions (create, read, update, and delete) that can be performed on a data source. POST, GET, PUT, DELETE.
>
> Endpoint is a specific address (for example, https://hotels-to-stay.com/best-hotels-paris), by referring to which (with certain request method) you get access to certain features/data (in our case – the list of best hotels in Paris).
>
> Example:
>
> Twitter also provides a REST API which a developer can query to source the latest tweets, or provide a search query that will return the results in JSON format.
>
> Instagram API permits your applications to retrieve user tags, photos, account and much more.
>
##### Complete Answer:
>
> [Link to answer 1](https://rapidapi.com/blog/how-to-use-an-api-with-javascript/)
>
> [Link to answer 2](https://blog.logrocket.com/axios-or-fetch-api/#:~:text=To%20send%20data%2C%20fetch(),set%20in%20the%20options%20object)
>

<br />

### 10. API vs Restful API?
>
##### Short Answer:
>
> The first thing to understand is that API is the superset while REST API is the subset. This means all REST APIs are APIs while not all APIs are REST APIs.
> 
> REST stands for Representational State Transfer while API stands for Application Program Interface.
>
> While API is basically a set of functions and procedures that allow one application to access the feature of other application, REST is an architectural style for networked applications on the web.
>
##### Complete Answer:
>
> [Link to answer 1](https://www.freelancinggig.com/blog/2018/11/02/what-is-the-difference-between-api-and-rest-api/)
>

<br />

### 11. What is 'this keyword in js'?
>
##### Short Answer:
>
> Every javascript function while executing has a reference to its current execution context, called this. Execution context means here is how the function is called.
>
> ```js
>function bike() {
>  console.log(this.name);
>}
>
> var name = "Ninja";
> var obj1 = { name: "Pulsar", bike: bike };
> var obj2 = { name: "Gixxer", bike: bike };
>
> bike();           // "Ninja"
> obj1.bike();      // "Pulsar"
> obj2.bike();      // "Gixxer"
>
> ```
> 
>
##### Complete Answer:
>
> [Link to answer 1](https://codeburst.io/all-about-this-and-new-keywords-in-javascript-38039f71780c)
>
> [Link to answer 2](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/this)
>
> [Link to answer 3](https://medium.com/better-programming/understanding-the-this-keyword-in-javascript-cb76d4c7c5e8)
>
