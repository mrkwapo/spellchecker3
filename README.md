Spellchecker whiteboard:

Create an html page that will have: -an input box for a user to type a word -a button to submit the search term -an an area to display results

Create a file that contains correctly spelled words.

Create a javascript file that will: -access the user input -connect the file containing correctly spelled words -use the user input and query the dictionary file for the search term

use conditional statements to respond if the word is spelled correctly and if it is not spelled corredctly
Packages and dependencies needed:

express (https://expressjs.com/) used to create a server
nodemon (https://nodemon.io/) Saves time by automatically reloads your server when new changes are made
axios
Install and set up Express (also see this link for instructions on installing and using express: https://expressjs.com/en/starter/installing.html)

cd into your project directory and type the following into the terminal:

npm init // which will initilize node package manager and create a package.json file //This command prompts you for a number of things, such as the name and version of your application. For now, you can simply hit RETURN to accept the defaults for most of them except index.js which you can rename by typing example.js or whatever

Next type in the following to install express

 npm install express --save
Install and set up nodemon

1.Open your package.json file to add the following to your scripts object:

    "server": "nodemon server.js"
In your terminal, type:

 npm install -g nodemon
install axios
