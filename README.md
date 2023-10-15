# Ecommerce


# Description
This is a database for an e-commerce site using sequalize and with express usage as well.

# Installation

git clone and cd into using vscode

Users will need nodejs, mysql and insomia

npm init -y then npm install

Before access to databas, must creat a .env file. One is with example on how it should be. You will have to put their MySQL username and password as a string in the .env file.

Once created go into your mysql with this and go into the schema
(mysql -u (MySql username) -p) then this (source db/schema.sql;) and quite after (quit;)

Do npm run seed
npm start
node serever

should get the following message App listening on port 3001! and running in localhost:3001.

# Usage
open up in insominia to access and use the database


Use localhost:3001/api/products, localhost:3001/api/tags, or localhost:3001/api/categories in the URL.