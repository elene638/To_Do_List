# To Do List version-2

This project follows material from [the Complete Web Development Bootcamp](https://www.udemy.com/course/the-complete-web-development-bootcamp). There are some variations compared to the course instructions since some of the code did not work in the newer MongoDB version.

## Common Usage
The app allows to:
- add new item to already existing list on the homepage
- visit about page, which is populated with Lorem Ipsum text
- create custom pages with new list and populate it
- delete already existing or new items from list

---
## Requirements
- Node 16
- Git
- Heroku CLI
- MongoDB Shell
---
## Common setup
Clone the repo and install the dependencies.
``` 
git clone https://github.com/elene638/To_Do_List.git
cd To_Do_List
```
``` 
npm install
``` 

---

## Deploy to Heroku

The app can be deployed to Heroku, there is Procfile already prepared. Follow instruction from [here](https://devcenter.heroku.com/articles/getting-started-with-nodejs) to successfully deploy the app.

---

## Run locally

In the CLI run the following command to connect to MongoDB, but change `cluster0.xrkkl` this part since it's individual for each database
```
mongo "mongodb+srv://cluster0.xrkkl.mongodb.net/myFirstDatabase" --username <username>
```
In another window of the CLI run the command 
```
nodemon app.js
```
Open the browser and follow the link 
```
http://localhost:3000/
```
