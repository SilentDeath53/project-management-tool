# Project Management Tool
1- Make sure you have Ruby and Ruby on Rails installed on your machine.

2- Open your terminal and run the following command:

rails new project-management-tool


3- cd project-management-tool

4- Generate the necessary models:

rails generate scaffold Project name:string description:text
rails generate scaffold Task name:string description:text project_id:integer

5- rails db:migrate

# Created By Silent Death_53
