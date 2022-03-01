# Object-Relational Mapping (ORM): E-Commerce Back End 

      
![GitHub license](https://img.shields.io/static/v1?label=License&message=MIT&color=blue&style=for-the-badge)

# Description
A mysql database and backend for an e-commerce store. Built with MySQL2, Express, Sequelize and dotenv.

# Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

# Installation 

`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`

# Usage

Run the commands in the terminal of theproject and answer the prompted questions:

`mysql -u (username) -p`

Enter your password.

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`

When you run node index in your terminal, you will be made to answer a series of questions. Once all questions are answered navigate to the dist folder as it will house the readme file that your responses will be stored to. Open a preview of your new README and ensure that everything is spelled correctly and that the links to your GitHub page and email work otherwise you will need to run the application again and reinput the correct information.

# License

> This project is using the MIT license.

# Contributing

If you would like to contribute to this project, fork this repository and clone your forked repository into your local machine, set the upstream as this repository and the origin as your forked repository, then use git pull upstream main to sync your local repo with the project repo. Then create a new feature branch which will house all your edits. Once finished push commits to your forked repository and then create a pull request! All contributions are encouraged!

# User Story

```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

# Acceptance Criteria

``` 
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```
# Walkthrough

> [Checkout the walkthrough](https://www.loom.com/share/f0aadc6a40814c84b4c894efacb9e704)

# Questions
Please contact me through the following methods!

> [My Github account](https://github.com/charles-nyabeze)

> <a href="mailto:charlesnnyabeze@gmail.com">My Email</a> 
