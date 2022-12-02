# E-Commerce Backend

## Description

The purpose of this project was to practice using Object-Relational Mapping to create an E-Commerce backend. This would allow a manager at an internet retail company to manage stock and compete with other e-commerce companies. While working on this project I was able to extend my learning and apply the sequilize content that I had recently learned.


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

The user can clone the code from the GitHub repo. Once the code is cloned and opened in a code editor the user should install all npm packages by running 
```
npm i
```
The user will also have to create a .env file in order to store their credentials for the connection. The user will have to input  DB_NAME, DB_USER, and DB_PW variables with their credentials as the values. The next step is to run the schema file with mysql. The user will enter their mysql shell and run
```
SOURCE db/schema.sql 
```
from the root of the project. The user can now exit the mysql shell. The user can seed the database running
```
node run seed
```


## Usage

To invoke the application the user can run 

```
npm start
```
If the user wants to run in a dev environment so the server refreshes after changes are made the user should run
```
npm run watch
```

[Walkthrough Video](https://drive.google.com/file/d/1ro02f1KIZOQ5avoKwb_JWVvGbfBU76F5/view?usp=sharing 'E-Commerce Backend Walkthrough Video')

## Credits

[README Template](https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide 'Professional README Guide')

## License

N/A