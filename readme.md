## Project Overview

The project of this course will be to build a register of stock exchange negotiations. We will register new deals and they will be imported from specialized services, all applying the functional and object-oriented paradigms while, at the same time, using the best of both worlds.

At first glance, the scope of our application may seem quite reduced, but it is enough to apply new features of the JavaScript language, or ECMAScript 2015 (ES6), technically speaking. In addition, we will organize our code in the MVC model (Model-View-Controller), apply design patterns, program asynchronously with *promises, render templates, and work with proxies, among other things.

First we use document.querySelector which is a Dom API that allows us to fetch a DOM element using a CSS selector.

### Model
> The models' responsibility is to represent the business. You are also responsible for accessing and manipulating the data in your application.
- Object.freeze()
- var and let 
- defensive programming 
- get syntax
- constructor
- private attributes must use the prefix _ (underline)

### Controller
> The Controller layer handles requests from users. It is responsible for rendering a response with the aid of both the Model and the View layer.
> A controller can be seen as a manager that ensures that all resources needed for completing a task are delegated to the correct workers. It waits for petitions from clients, checks their validity according to authentication or authorization rules, delegates data fetching or processing to the model, selects the type of presentational data that the clients are accepting, and finally delegates the rendering process to the View layer.
- looping through the DOM many times
- Date object
- spread operator
- arrow functions

### Date Helper
> Helper.js is a Class file that contains several commonly used methods with static type. The advantage of creating such a helper class is that we can write all required common methods in a single place and can use them in multiple components. It increases code reusability and maintainability.
- Single responsability 
- Static methods 
- Date Conversion
- Template Strings
- Fail Fast

### View Implementation 
> The View renders a presentation of modeled data. Being separated from the Model objects, it is responsible for using the information it has available to produce any presentational interface your application might need. For example, as the Model layer returns a set of data, the view would use it to render a HTML page containing it, or a XML formatted result for others to consume.
- innerHTML: converts a string to DOM elements
- dinamic  tr construction in the template strings
- IIFE(Immediately Invoked Function Expression)
- reduce