# Angular 9 CRUD App

Simple CRUD application built with Angular 9.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

* [Node.js](https://nodejs.org/en/#home-downloadhead)
* [REST API backend sample project](https://github.com/didinj/coronavirus-restapi) - Used for data supply and exposes endpoints for data manipulation
* [MongoDB](https://docs.mongodb.com/manual/installation/) - NoSQL data storage
* [Visual Studio Code](https://code.visualstudio.com/download) - IDE / Text Editor

### How to run

To test the whole application, first, we have to run MongoDB server and Node/Express API in a separate terminal.

```
mongod
nodemon
```

Next, we have to build the Angular 9 app using this command. 

```
ng build --prod
```
Then run the ES5 build of the Angular 9 app.

```
ng serve --open
```

Navigate to [http://localhost:4200/cases](http://localhost:4200/cases) and explore the app.

##### Built With

* Angular 9
* Bootstrap 4
* SCSS
* HTML5

###### Built from article [Angular 9 Tutorial: Learn to Build a CRUD Angular App Quickly.](https://www.djamware.com/post/5e435e84a8d0ef4300ffc5f6/angular-9-tutorial-learn-to-build-a-crud-angular-app-quickly)
