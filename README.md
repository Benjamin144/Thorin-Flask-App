[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/Benjamin144/Thorin-Flask-App)

# Thorin-Flask-App

Flask is a small framework that allows us t build web apps.
All it does when our index page is called, is just return the text, "Hello, World".
This is helpful for showing how a Flask app is put together.

### Rendering HTML Code ###
Returning HTML code from a Flask function. It also allows us to render HTML code from the server By returning a string that contains HTML tags

### Routing ###
Routing allows us to swich between views using URL, By creating routes

### Template Inheritance ###
Allows us to inherit code by creating a base template and using {% extends 'base.html' %} in a child template

### Styling Our Templates ###
Taking the styles of the theme and adding them to our own site Styles the content on our site, By using the theme that we got from Start Bootstrap

### Making The Design Our Own ###
Styling our site, Customising the theme, By modifying the theme to suit our needs

### Passing Data From A View To A Template ###
Information that we can provide to a template from the backend, Allows us to generate information inside our view and inject it into a template by passing named arguments to the render_template function

### Using For Loops Inside HTML ###
This is a template tag that allows us to perform logic inside of our HTML templates. In this case, it allows us to use a for loop inside of our HTML by using the {% %} template tags

### Reading From A JSON File ###
A JSON file that will contain our data that will allow us to store data in a JSON file by creating a .json file and adding our data to the file

### Iterating Over Our JSON Data ###
A for loop to iterate over our JSON data, It allows us to re-render the same HTML code for each item in a list (or iterable, By passing the data to the template and using the {% for member in company_data %} tag

### Using If Statements Inside Our HTML ####    
The if template tag, allows us to use if statements inside our templates, by using the {% if some_condition %} tag and the closing {% endif %} tag

### Advanced Routing ###
Additional routing parameters, that allow us to create more specific routes, by passing part of a route to a function as an argument

### Creating A Form In A Template ###
This is an HTML form, that allows us to submit data to the server by creating a new form!

### POST ###
The POST request method, allows us to post infomation to our server, by specifying the POST method on the form element and handling it on the backend

### Providing feedback to the user ###
I will use a 'flash' function, that allows us to provide users with feedback, by using the flash function!

### Signing up to Heroku ###
Experimenting with Heroku's deployment platform that will allow us to deploy our code to a server for all the world to see!

### Creating a new Heroku app ###
Do this from the heroku apps command, Creates a new app on Heroku by creating a new app on the Heroku dashboard

### The Heroku Toolbelt ###
The Heroku Toolbelt, where stuff happens! It allows us to us Heroku functionlity from the CLI. Firstly, we need to log from the CLI and then we'll heroku commands to access different pieces of functionality

### Pushing to Heroku ###
Our Heroku deployment, pushes our code to the Heroku server by adding a new git remote that points to the server and pushing to that remote

### Adding A requirements.txt File ###
The requirements.txt file that keeps track of the dependencies that I have installed for this project, I am using the pip3 freeze --local > requirements.txt command