# gostack11-firstBackendApp

This back-end program allows you to list, create, edit and delete projects of your own choice and saves it into an array of Projects.
Before each request, a middleware is called and returns a console log with the HTTP method that was called and its time. Besides that, the program uses another middleware to check that the ID sent in the routes really is an UUID.

## Libraries used in this project
### Production
- Express
- uuidv4 - to generate uuids

### Development
- Nodemon - to automatically restarts de node server when the file is saved.

## How to run this program?
1- you need to clone this repository using 'git clone https://github.com/PauloFRPDev/gostack11-firstBackendApp.git'
2- open the project folder into your favorite IDE
3- run 'yarn' if you use yarn or 'npm install' if you use npm
4- run 'yarn dev' or 'npm run dev'
5- be happy 😃