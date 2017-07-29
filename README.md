# Welcome to Blockbuster!

In this fullstack review application, we will be bringing Blockbuster back from the dead. You will be setting up a server and a database, creating a RESTful API for their inventory, and rendering views on the front end to see the data. 

## Tech Stack
* Express
* MySQL
* Sequelize
* React / Angular
(This full stack review does not use an external API)

## Task
Go through the file structure and fill in the "TODO"s throughout the application
**Note about the branches:
There are three branches in this repo:
1. Barebones Scaffold - If you are feeling comfortable building an app with a skeleton given to you, feel free to check out into this branch to practice with only the barebones information given to you.
2. Master - This branch has basic information already filled in and all you will be required to do is fill in the TODO's
3. Solution - Self exlanatory

Feel free to check into the branch that matches your current comfort level!

## To Do List:

**Try to build the app without looking at this todo list, but if you're feeling lost at what direction to go, go ahead and look at this list to guide you**

1. Set up a server and get it to serve up a static file (depending on your front end framework of choice, make sure it's pointing to the right folder)
2. Set up a database; the solution code will use Sequelize but feel free to choose whichever ORM you wish. 
  Your movies table should include the following information:
    * Title
    * Number of Copies
    * IMDB Rating
3. Write routes and controllers for your server to interact with your database. Use Postman to test your routes; At minimum, you want to:
    * Post a movie to the database
    * Get all movies to the database
4. Render front end components to utilize your routes. 
    * Create your views so that you can either choose an option to view all movies, or
    * Choose an option to add a movie to the database
5. Style!

## Extra
This review only covers barebones concepts. If you'd like, feel free to build on top of it, for example:
* add put and delete routes
* create functionality for users and add relationship between users and movies (i.e. so that users can eventually "check" movies out)
* add routes and more front end components to interact with user routes
* add authentication
* write tests!
