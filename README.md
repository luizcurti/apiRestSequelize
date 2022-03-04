# API Rest Sequelize
Rest API with Sequelize and JWT for student registration

1 - Open a terminal and enter the apiRestSequelize directory and run the command 'docker compose up' to upload the MYSQL database. "Must have docker on your machine"

2 - Before starting the project, create the SCHEMA/DATABASE 'school'

3 - Open a new terminal and enter the apiRestSequelize directory and run " npm i " to install the modules needed to run the project

4 - Run the command to create the tables and insert an initial user as administrator
" npx sequelize db:migrate && npx sequelize db:seed:all "

5 - Start the project with "npm un dev"

6 - Import the Insomnia.json file into your Insomnia. All routes for testing the application are there.

7 - The application process is very simple.
We have the "users" who are like administrators. They can register, edit and delete students. A student may have one or more photos on their profile. Some routes only work with the administrator logged in and with their active token.
