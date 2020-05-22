# HelloWorld


run == npm install 

Step 1: ng new hello-world
step 2: MOve inside the folder hello-world
step 3: ng serve
step 4: http://localhost:4200/  you can see your angular running 

=== 
Now lets create Component 
======
step 1: ng g c header
you can see , HeaderComponent is added in your app.module.ts 
step 2: add "  <h1>Good Morning ! Module Imported</h1> "  header.component.html
step 3: delete everything from app.component.html 
step 4: write <app-header></app-header> => we are now calling this header app which is just created
step 5 : ng serve


 


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 9.0.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

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
