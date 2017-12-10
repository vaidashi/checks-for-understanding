## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?
var vs. let declaration of variables

2. What's the difference between asynchronous and synchronous JavaScript? 
Async JS deals with certain actions being performed independant of other actions, w/o affecting them and causing page refreshes. It allows you to perform actions in a multi-threaded fashion through the browser vs. sync JS where you perform only one sync action (consisting of series of actions). 

3. What are the four pillars of Object Oriented programming?
Abstraction, Inheritance, Encapsulation, Polymorphism.

4. What are some tools available in JavaScript to help you write object oriented code?
Prototypes and es6 syntax for class definition vs. es5 constructor functions.

5. What are some key concepts to be aware of when refactoring your JavaScript?
Don't repeat yourself, SRP, long functions, long and/or deeply nested conditionals.

6. What's a callback function and what are some reasons when we use/need callback functions?
Callback function is a function that is passed as an arguement to another function. Callbacks can allow you to peform asyc actions.

7. What are the different scopes of variables in Javascript? When would you want to define global variables?
Global and local variables. You would want to define a global variable if something will not change after it's defined and if it will be utilized more that once.

8. What's the difference between `==` and `===` in JavaScript?
Equal vs. strict equal. The former checks if the value is the same , whereas the latter checks if the value and object type are the same.

9. Why do front end frameworks exist?
To have a more appealing way to interact and display content.

#### Review  

10. Why do people say "HTTP is stateless"?
It doesn't store any information, it processes requests but doesn't by itself store the requests/responses in memory.

11. Describe a RESTful API.
Relies on stateless protocol, objects == resources, requests should be HTTP get, post, put/patch, delete.

12. What are some main characteristics of a team following an agile workflow?
Adjustments along the way as necessary, segmented project deliverables (sprints), continous communication with customer/client and project team. 

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?
Pros: you don't save any user PII yourself, 
Cons: you are dependant on another site, if it is down , then your users can't sign on unless you have your own native auth process.
