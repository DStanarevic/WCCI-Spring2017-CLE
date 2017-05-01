## Topics
- What does MVC stand for?
- Why use MVC?
- When should MVC be used?
- What are the steps to creating an MVC project?
- What role does the Model play?
- What role does the View play?
- What role does the Controller play?
- What is Razor?

## Goals
 - To understand MVC conceptually
 - To understand Models
 - To understand Views
 - To understand Controllers
 - To understand when you would use MVC

### Model
- The model contains business logic for the web application. 
  - For example, the classes you create for your application (with attributes and methods) belong in the model.
- The *Model* represents what is being displayed. If you check your email via Gmail (or a similar web client), the {content} of your emails represents the model.

### View
- The *View* is how the model is shown to the user. The interface you're looking at when you're checking email, including its styling (fonts, borders, etc) represent the view. Different people checking their email will see the same interface, but different content. Different people will see the *same* view but *different* models.
- This is the front end of the application where HTML, CSS, JavaScript languages belong.

### Controller
- The controller is responsible for controlling the flow of the program.
  - The controller controls the interactions between the models and views.
- The *Controller* is the glue that holds the two together. When you want to create or delete an email in your email client, you're sending a message to the controller. It is responsible for updating the model (creating or deleting the email), then refreshing the view (showing you what you see on the screen).

## Do It
- In-Class Acting out MVC (great work Jazmyne, Lily, Noah and Stefanie!)
- 

## Student Resources & Practice Problems
- [Creating an ASP.NET MVC Web Application](https://docs.google.com/presentation/d/1yqn9NZOcxetfKugCa_jkCg2vbTnDQMY14IVDMBR9mqA/edit?usp=sharing)
- [TutorialsPoint](https://www.tutorialspoint.com/asp.net_mvc/index.htm)
- [W3Schools - MVC](http://www-db.deis.unibo.it/courses/TW/DOCS/w3schools/aspnet/mvc_intro.asp.html)
- [W3Schools - Razor](http://www-db.deis.unibo.it/courses/TW/DOCS/w3schools/aspnet/razor_intro.asp.html)
