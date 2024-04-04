# MyApp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.1.6.

## Install Angular CLI globally using npm

Run `npm install -g @angular/cli`

## Create a new Angular project

Run `ng new myNewAPP`

## Navigate to your project directory

Run `cd myNewAPP`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Remember

To have Node.js and npm installed on your system before creating an Angular app and make sure you have the correct versions.

## Building Blocks of an Angular Application
**Components**
- *Controls a view*

**Data Binding**
- *Used to coordinate parts of a template with parts of a component*

**Dependency injection**
- *Method of provisioning a new instance of a class with all the necessary dependencies that are needed*

**Directives**
- *The DOM is configured with the instructions that are provided by the directive*

**Metadata**
- *Metadata instructs Angular in the process of creating a class*

**Modules**
- *Assist in managing an application into united blocks of functionality*

**Services**
- *Can be anything that the application needs in terms of values, functions and features*

**Templates**
- *Templates provide the framework that provides Angular the instructions to render components*

## Deep Diving DIRECTIVES
- One of the core features in Angular
- Directives allow AngularJS the scalability of extending the HTML with attributes
- Built-in directive that can be used right away and can provide various functionality to applications
- Attaches behaviour to a DOM element in the application
- Directives can provide the following
    - Replace or exten the HTML element in the application
    - Behaviours
    - Data binding to the scope of the application
### Core Directives
**Application**
`ng-app` 
- *designates the root element of the application, and its usually placed on either html or body tag*
`ng-controller`
- *binds a view to controller class which essentially limits the scope of a controller to the current view and its parent, if any.*
  
**Binding**
`ng-bind`
- *instructs Angular to populate the contents of an HTML element, with the value of the given expression. Using double curly braces {} is essentially the equivalent of using `ng-bind`*
`ng-model`
- *is a directive that binds an element such as input or select element to a given scope property, serving as the key directive behind Angular's MVVM architecture.*
`ng-init`
- *enables the evaluation of a given expression in the current scope*
`ng-src`
- *enables evaluation of expressions within the source attribute of lements, such as the image element*
`ng-style`
- *its a directive enables applying inline CSS styles based on the evaluation of an expression*

**Form**
`ng-minlength*
- *enforces minlength value*
`ng-maxlength*
- *enforces maxlength value*
`ng-required`
- *set the required attribute to an HTML element based on the evaluation of a Boolean expression.*
`ng-list`
- *converts a value into a delimited string or array of strings
Other form directives:
`ng-true-value`, `ng-fales-value`, `ng-options` and `ng-submit`

