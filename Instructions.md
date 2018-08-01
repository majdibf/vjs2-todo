# install vue-cli
$ npm install --global vue-cli

# create a new project using the "webpack" template
$ vue init webpack todo-app

# install dependencies and go!
$ cd todo-app
$ npm install

# to serve the app, run
npm run dev

# open browser and direct to:
http://localhost:8080

# Styling
To style our application we will use Semantic.
Semantic is a development framework that helps create beautiful, responsive layouts using human-friendly HTML.

We will also use Sweetalert to prompt users to confirm actions.
Sweetalert is a library that provides beautiful alternatives to the default JavaScript alert.

=>Add the minified JavaScript and CSS scripts and links to your index.html file found at the root of your folder structure.


# A component file consists three parts:
 Template, component class and styles sections.
     The template area is the visual part of a component.
     Behaviour, events and data storage for the template are handled by the class.
     The style section serves to further improve the appearance of the template.

# Importing Components
To utilize the component we just created, we need to import it in our main component. Inside of src/App.vue make the following changes just above the script section and below the template closing tag.
