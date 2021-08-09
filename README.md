My Note-Taker


Description :
This is a simple Note Taker application that allows users to add, view saved notes and also delete the notes if the user don't need that note anymore. This application uses an express backend and save and retrieve note data from a JSON file.



Table of Contents
Demo
Technology
Usage
Features
License
Contribution
Questions
User Story
AS A user, I want to be able to write and save notes.

I WANT to be able to delete notes I've written before.

SO THAT I can organize my thoughts and keep track of tasks I need to complete
Business Context
For users that need to keep track of a lot of information, it's easy to forget or be unable to recall something important.

Being able to take persistent notes allows users to have written information available when needed.

Demo :
Note Taker

Application Preview :
Main Page	Saved Notes	Delete Note
Main Page	Saved Notes	Delete Note
Technology :
1. Express.js :

Web Applications : Express is a minimal and flexible Node.js web application framework that provides a robust set of features for web and mobile applications.

APIs : With a myriad of HTTP utility methods and middleware, creating a robust API is quick and easy.

Performance : Express provides a thin layer of fundamental web application features, without obscuring Node.js features.

2. Node.js :

Node.js is an open-source and cross-platform JavaScript runtime environment.

A Node.js app is run in a single process, without creating a new thread for every request.

Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking.

3. uuid : Creates random unique id's.

Usage :
Clone this repository to use this application on local machine.

To install necessary dependencies, run the following command :

npm i
The application will be invoked with the following command: This will start localhost server on PORT 3000.
node server.js
Open browser and type http://localhost:3000/ to run this application on your local machine.
Features :
Used 'Express.js' to build server

Used 'fs(File System)' module to read and write from 'db.json' file.

Used uuid npm package to give unique id to each note.

Application is deployed on heroku : Heroku is a container-based cloud Platform as a Service (PaaS). Developers use Heroku to deploy, manage, and scale modern apps.

License
This project is licensed under MIT license.

Contribution
Pull requests are always welcome!

Questions
If you have any questions about the repo, open an issue or contact me directly at Email.