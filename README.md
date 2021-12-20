# 13 Object-Relational Mapping (ORM): E-Commerce Back End


## Usage and Installation

Run the following commands in the termingal to get this up and running. Then you can check the endpoints in Insomnia or Postman!
```
npm install
```

```
mysql -u root -p
```
Enter your password for this mysql server
```
source db/schema.sql
use ecommerce_db
exit
```

```
npm run seed
```

## Getting Started

You’ll need to use the [MySQL2](https://www.npmjs.com/package/mysql2) and [Sequelize](https://www.npmjs.com/package/sequelize) packages to connect your Express.js API to a MySQL database and the [dotenv](https://www.npmjs.com/package/dotenv) package to use environment variables to store sensitive data.

Use the `schema.sql` file in the `db` folder to create your database with MySQL shell commands. Use environment variables to store sensitive data like your MySQL username, password, and database name.

