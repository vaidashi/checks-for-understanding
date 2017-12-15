## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?
It's a server side environment for JavaScript. 

2. What is Express? What is Express similar to in the Ruby world?
Express is similiar to Sinatra from Ruby in that it's a framework that sits on top of Node and makes it easier to work with.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.
app.get('/api/v1/foods', foodsController.getFoods)

4. What do we use Knex for?
It's similiar to ActiveRecord, allows you to interact with a database in Node.

5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?
Having a file for your routes, a controller file for your actions (ideally RESTful), and a model file for you database interactions.

6. How do you execute raw SQL in node?
 knex.raw('some SQL'),

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?
PROS: keeps your codebase more concise, focused on its intent (UX vs. backend management)
CONS: can't think of any


#### Review  

8. Describe DNS.
Domain Name Server, it translates url name into IP address. 

9. What does writing clean code mean to you?
Having functions that focus on one specific action and not multiple. Abstracting out functionality that it is used across multiple resources and instead of repeating it multiple times. Having class, var, function names that clearly indicate what value they contain.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.

Hotels, rooms, reservations, guests = database
Hotels have many reservations, reservations is a join that belongs to a room and a guest.





