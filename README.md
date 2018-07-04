# MeanApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.1.

#Install application

type npm install into the console from the root directory and from the directory ./MeanApp

## Run Application

Run `npm start` from the directory ./MeanApp for to run the Mean Application. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.



# Api request

GET  '/users'  'http://localhost:3000'  return the list of users from  Mongodb database

GET  '/user:id' 'http://localhost:3000' return the user with id ':id' from  Mongodb database

POST  '/user'   'http://localhost:3000' send a new user to save into Mongodb database

PUT '/user:id'  'http://localhost:3000' update the user with the id ':id' into Mongodb database

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
