# React Questions

### 1. Reactjs
>
##### Short Answer:
>
> A js library. 
> Pros: 
> React make it painless to create interactive UIs. Design simple views for each state of ypur application. React will efficiently update and render just the right components when your data changes.
> Declarative views makes your code more predictable and easier to debug.
>
> Build Encapsulated components taht manage their own state, the compose them to make comples UIs. Since the logic is written in javascript you keep state out of the DOM.
>
>
##### Complete Answer:
>
> [Link to answer 1](https://reactjs.org/)
>

<br />

### 2. Difference between Props and State
>
##### Short Answer:
>
> Props are variables passed to it by its parent component. Also it is Inmutable
>
> State is still variables but directly initialized and managed by the component. Also it is Mutable
>
##### Complete Answer:
>
> [Link to answer 1](https://flaviocopes.com/react-state-vs-props/)
>
> [Link to answer 2](https://stackoverflow.com/questions/27991366/what-is-the-difference-between-state-and-props-in-react#:~:text=Basically%2C%20the%20difference%20is%20that,a%20function%20with%20certain%20parameters.)

<br />

### 3. Lifecycle React
>
##### Short Answer:
>
> It’s very important to free up resources taken by the components when they are destroyed.
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
> [Link to answer 1](https://reactjs.org/docs/state-and-lifecycle.html)
>

<br />

### 4. Redux
>
##### Short Answer:
>
> A Predictable State Container for JS Apps.
>
> Redux improves the aspects where React doesn’t do well. Ideally, the data in a component should live in just one component, so sharing data among sibling components becomes difficult.
>
> Now imagine what happens when a state has to be shared between components that are far apart in the component tree. The state has to be passed from one component to another until it gets to where it is needed.
>
>
> It’s clear that state management gets messy as the app gets complex. This is why you need a state management tool like Redux
>
> The way Redux works is simple. There is a central store that holds the entire state of the application. Each component can access the stored state without having to send down props from one component to another.
>
> There are three building parts: actions, store, and reducers.
>
> **Actions:** actions are events. They are the only way you can send data from your application to your Redux store. Actions are sent using the store.dispatch() method. Actions are plain JavaScript objects, and they must have a type property to indicate the type of action to be carried out.
>
> **Reducers:** Reducers are pure functions that take the current state of an application, perform an action, and return a new state. As pure functions, they do not change the data in the object passed to them or perform any side effect in the application.
>
> **Store:** holds the application state. There is only one store in any Redux application. You can access the state stored, update the state, and register or unregister listeners via helper methods.
>
>
##### Complete Answer:
>
> [Link to answer 1](https://redux.js.org/introduction/getting-started)
>
> [Link to answer 2](https://blog.logrocket.com/why-use-redux-reasons-with-clear-examples-d21bffd5835/)
>

<br />

### 5. Testing
>
##### Short Answer:
>
> 
>
>
##### Complete Answer:
>
> [Link to answer 1](https://babeljs.io/docs/en/)
>
