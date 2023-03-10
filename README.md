
# Object-Relational Mapping (ORM): E-Commerce Back End 
  
<p align="center">
    <img src="https://img.shields.io/github/repo-size/Paul-Dimenshion/orm-back_end-pd-unb" />
    <img src="https://img.shields.io/github/languages/top/Paul-Dimenshion/orm-back_end-pd-unb"  />
    <img src="https://img.shields.io/github/issues/Paul-Dimenshion/orm-back_end-pd-unbd" />
    <img src="https://img.shields.io/github/last-commit/Paul-Dimenshion/orm-back_end-pd-unb" >
    <a href="https://github.com/Paul-Dimenshion"><img src="https://img.shields.io/github/followers/Paul-Dimenshion?style=social" target="_blank" /></a>
</p>
  
<p align="center">
    <img src="https://img.shields.io/badge/Javascript-yellow" />
    <img src="https://img.shields.io/badge/express-orange" />
    <img src="https://img.shields.io/badge/Sequelize-blue"  />
    <img src="https://img.shields.io/badge/mySQL-blue"  />
    <img src="https://img.shields.io/badge/dotenv-green" />
</p>

  
## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Table of Contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [Questions](#questions)

   
## Description

🔍 A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.
  🎥 The full movie file showing functionality of the application can be found below:
  [Walkthrough Video](https://watch.screencastify.com/v/JaUZiIoZChR67WRzxaNB)

## User Story
  
```
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```
  
## Acceptance Criteria
  
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

## Installation
💾   
  
`npm init`

`npm install mysql2`

`npm install sequelize`

`npm install dotenv`
  
## Usage
💻   
  
Run the following command at the root of your project and answer the prompted questions:

`mysql -u root -p`

Enter PASSWORD when promted

`source db/schema.sql`

`quit`

`npm run seed`
  
`npm start`


## Contributing
[Pavlo Demenshyn](https://github.com/Paul-Dimenshion)

## Questions
✉️ Contact me with any questions: [email](mailto:p.demenshyn@gmail.com) , [GitHub](https://github.com/Paul-Dimenshion)<br />