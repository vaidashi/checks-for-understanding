
1. How do we make flash messages display on a page?

  Through embedding the required text for them to render in our application view. Then we specify the flash messages we want and when we want them in a particular controller and action.

2. Where is cart information/temporary information usually stored?

  In a cookie.

3. What might be some reasons not to store cart in our database? Are there any reasons why we would want to persist that information?

  You may not want items in your database that didn't amount to an actual order which is something you would want to persist to the database.  A possible use case for storing the cart in the database would be if you want to keep a track of a user's interests in things they've added to their cart.

4. What is the purpose of the asset pipeline?

  Asset pipeline allows you to combine your assets such as (Javascript, CSS, etc). 

5. Why do we precompile our assets?

  To make things more efficient and faster for our application.

6. What do each of the following tags do?

```ruby 
<%= stylesheet_link_tag "application" %>
<%= javascript_include_tag "application" %>
<%= image_tag "rails.png" %>
```
  The first two will look into your stylesheet and reference the application.css and application.js files for any CSS styling   and or Javascript you want to incorporate. The image tag is a rails helper method that will retrieve the image you specify 
  from your images folder.


7. What are some of the elements of a great read me? What are some of the benefits of taking the time to update a readme for our project?
  
  Having screenshots, table of contents, troubleshooting guides, setup instructions, gem listing are some examples of a great
  readme. Benefits of having a great readme are that it will showcase your consideration for future visitors and downloaders 
   of your application and make it more likely for them to reference your project.


8. What are the top four accessibility issues that we as developers should be aware of?
  
  Blindness/ color blindness, mobility, hearing loss, cognition. 

9. `before_save` is an example of a what? Where in our Rails application would we find a `before_save`?
  
  It is a call_back. you would specify the the call_back in the controller of when you want it to occur, but what you want to  happen will be defined in the model. 

10. Given the following object, how would we create a scope for all users who are active?

```ruby 
User.create(name: "Happy", active: true)
```

  User.where(active: true).scoping do 
  "some code"
  end 

11. What is the difference between a scope and a class method?

  Scopes are class methods that you can modify easier than regular class methods regarding certain conditions/queries you want to return.
