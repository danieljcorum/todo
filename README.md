# Todo 101
Basic Fullstack Todo List App in nodejs to run on a Linux server

<H2> Dependancies </H2>
Mac:

- Git
- Homebrew
- NPM
- Express
- EJS

Windows:

- Git
- Idk yet

<H2> Local Installation </H2>

Mac:

- Install Homebrew at https://brew.sh/
- To install Git and NPM run `brew install npm git`
- Run `git clone https://github.com/danieljcorum/todo.git ~/Desktop/todo/`
- `cd ~/Desktop/todo/`
- To install the rest of the packages run `npm install -a`
- To start the app run `node server.js`
- Open chrome and go to http://localhost:8080

Windows:

- Idk yet

<H2>All About The Code </H2>

Server.js - Contains the basic rendering functions for the url routes

Views/index.ejs - Contains html injected with javascript to render string arrays and buttons to capture user data

All others are dependancies and meta data.

To zip `zip ./todo.zip ./*`
