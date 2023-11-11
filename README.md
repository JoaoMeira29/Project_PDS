# WatchEat

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.1.6.

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
# ProjectPDS - ...
***

## Ideas for the project:
* IMDB Knock Off (Thanks to access to the imdb API we can get a lot of information)
  * Friends, lists, requests for friends' lists;
  * Films/series watched, to watch, left;
  * Reviews, scores, rankings;
  * Listings, application of filters (genres, actors, directors, duration, etc...);
  * Developer tools:
	* CRUD for films/series;
  * Technologies
    * Node.js;
    * Espress.js;
    * Angular or React;
    * MySQL or SQLServer or MongoDB.
    * (MEAN or MERN if we go with MongoDB (benefits still to be ascertained))
  * Ideas:
  * Business rules:
    * User tier plan
      * normal free tier - normal access to the platform (specify later)
      * paid editor tier - normal access plus permission to edit films
      * the edit must be accepted by a moderator, if the edit is rejected you will have to redo it and resubmit it, if it is rejected 3 times you will be suspended for x time and subject to an internal evaluation
      * If you are rejected during the evaluation, you will once again become a normal user without being able to become an editor again.
      * You can change your plan at any time, unless you are (suspended, banned).
    * Setting a calendar of viewing times
      * When you set a future time to watch a film, you'll be given the option to order food at that time.
      * there will be integration with an external system where you can place an order for the time you have booked
      * In the event that the chosen food is not available (time, ingredients, closed caterer, etc.), you will be offered other options, where the order is restarted.
      * These orders will be linked to a courier, who can be visualised in the system.
      * It will be possible to cancel the order up to 1 hour before the booking time.
    * Film statistics (dashboard)

