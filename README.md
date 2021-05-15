#  Vaccine Matcher

You will be task with building an Express API to be consumed by a Front-end client.

## Project Discription: 

Vaccine Matcher is a third party app that connects people who want to get vaccinated with sites distributing the COVID-19 vaccine.

- [X] **Project Schema**

<p>
  <p>Draft:</p>
  <img src = https://github.com/ShrutiTamrakarTuladhar/Breakthrough-Server-Side-Project/blob/main/diagrams/idea_diagram.png width="600" >
</p>

<p>
  <p>ERD:</p>
  <img src = https://github.com/ShrutiTamrakarTuladhar/Breakthrough-Server-Side-Project/blob/main/diagrams/ERD-DIAGRAM.png width="600">
</p>


 
- [x] **Back-end**

- Build RESTful API routes that return data in a JSON format
- Encapsulated into classes

- Steps Taken:

  - Create database migratations
    - npm init -y (package.json)
    - npm i express (adding express modeules)
    - npm install --save-dev nodemon (adding nodde mon)
      change json pakage start to nodemon server.js
    - npm install ejs
    - npm install knex --save
    - npm install pg
    - node_modules/.bin/knex init (creates a knexfile.js)
    - update knexfile to connect to database
    - create a db.js file - pg promise is returned
    - node_modules/.bin/knex migrate:make name-here
    - create databese in postgress and edit file to connect
    - node_modules/.bin/knex migrate:latest
    - To see if table inside database run `\dt`
    - Add test data to tables
    - Create seed files and run seed
    - node_modules/.bin/knex seed
    
  - To setup enviroment:
    - install dot-env
    - create a .env file
    - USER = ''
    - DATABASE = ''
    - PASSWORD = ''

- [x] **Front-end**
  - React

- [ ] **Stretch features**
  - Registration and Authentication
  - Insurance table
