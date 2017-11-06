##Deploying a simple app with heroku

First create a .gitignore file in your project root directory

in your command line type : touch .gitignore 

in the .gitignore file add node_modules

please don't commit the node_modules folder in your repo 

Better is you can clone the entire repo or star and fork the repo and start your own static file journey by modifying the files in the public directory.

This project is simple  client side implementation.

Creating a simple http server for serving static file

1.Create the simple node server by copying the code in index.js and replicate the package.json

2.Then create a heroku account

3.then login via heroku 
In your command line type the following command :

1. heroku login

-- Enter your email id 


-- Enter password



Then from your project directory execute the command line by line.

1. git init

2. git add .

3. git commit -m "Intial commit"

4. heroku create

5. git push heroku master

6. heroku open 

and then navigate to your static pages

Like in this example 

I have one index.html , form.html and test.html

which can be accessed via ::


1.https://obscure-woodland-17425.herokuapp.com/

2.https://obscure-woodland-17425.herokuapp.com/form.html

3.https://obscure-woodland-17425.herokuapp.com/test.html
 
If you have any doubt you can contact sagar13912@gmail.com

