## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's the most useful thing you learned from completing the intermission week work?
How functions and loops work in JS.

2. What are some tools to help debug JavaScript code?
debugger, console.log, alert, developer tools

3. What are some tools you need in order to unit test your JavaScript?
Installing and requiring the different libraries. Chai as an example and requiring the commands (expect, assert) that you would want to use.

4. What is the syntax for invoking a function?
functionName();
//If function takes in an arguement then you pass in inside the paras.

5. What is CORS?
Cross Origin Resource Sharing. Seems to be the protocol for how one app controls its assets from another app, allowing it to access that resource or not? 

6. How do we enable CORS?
Depending on the framework being used, there exists a specific command/file you utilize?

7. What's `this` in JavaScript?
It's a special reserved term. References it's parent object and is dependent on the context of where it's referenced.

8. What is Webpack and why is it useful?
Similiar to the Asset Pipeline in Rails, it compiles everything and renders a file that the browser takes in.

9. When/why do you want to use event delegation?
Deals with event bubbling. If you set an event listener on a parent object, the child elements will then inherit that functionality.

10. What's `npm` and what do we use it for?
Package manager for JS. Makes working on larger projects easier?

#### Review  
11. What's the MVC design pattern? Describe each part of MVC.
It's an OOP methodology for relating the UI to the underlying data of an app. 

Model = underlying database interactions and logic
View  = represents the elements for the UI
Controller = coordinator for your app connecting the model and view

12. What are a few ways to optimize a Rails application?
Speed, improving upon functions or query methods that may take a significant time to run and utilizing a tool such as Redis in order to observe which pages take long to render.

13. What's a background worker? When would we want to use a background worker?
Background Workers are a tool that allow you to perform certain actions after an event occurs and that you may not need the specific response immediately. An example may be sending an confirmation email to a new user once they sign up as a member for your site.
