Employee Manager
Summary
Employee Manager is a CLI app for managing human resources. You can add, edit, and delete employees, departments, and roles, and manage the associations between them. See the database schema for more information about how it all works together.

Prerequisites
NodeJS
MySQL
Installing
Run the following commands in your preferred CLI to install the Node package and all dependencies:

git clone (https://github.com/ashleymullikin/employee-tracker)
cd employee-manager
npm i
Create a new file called .env that will store your MySQL server information:

touch .env
Format the contents of .env as follows, substituting your MySQL server information where applicable:
DATABASE = employee_db
DATABASE_HOST = localhost
DATABASE_USER = root
DATABASE_PASSSWORD = "DBPASSWORD"

Import the database schema and optional demo data

node index.js

database schema: ![image](https://user-images.githubusercontent.com/109765172/197233953-bcbef618-c8cd-461d-a363-33fa276bd5bf.png)

Working image, I was struggling with a bug I could not figure out, but this is what the deployed application would look like.
![image](https://user-images.githubusercontent.com/109765172/197234151-07a9bfba-0e5c-4d35-84e4-db5047b3a5d6.png)

here is a video of the codes and error: 

video link: https://drive.google.com/file/d/1CPBc75r17mmVdMI7X7LrhH4WKNO-IwH7/view


back up video link: chrome-extension://mmeijimgabbpbgpdklnllpncmdofkcpn/app.html#/files/f355474f-60ca-474c-yb8c-3e395e03de47


Learning Points:
I spent a lot of time reading up on MySQL JOIN, COUNT, and GROUP_CONCAT statements to effectively connect the different points of data from the different tables in the manner I desired. I am still struggling on figuring out how to properly use the .env files and how to call/build them in



Built With:
JavaScript
NodeJS

Node Packages:
MySQL
Inquirer
DotEnv
Console.Table
