# ngComponentRouter
Angular 2 Component Router for Angular 1

This is an extract directly built from Angular 2 source code without modification. Adding this as an npm package, because Angular hasn't released an official version yet. 

## Based on Angular 2 Commit
e72dc16dbe4afa3428c4524901cbd2501a84a98b

## Procedure of Extraction
As discussed on https://github.com/angular/angular.js/issues/12926.

- Install gulp globally `npm install -g gulp@latest`
- Clone the angular 2 repo: `git clone git@github.com:angular/angular.git angular2`
- Go into the angular2 directory and install the dependencies `cd angular2` and `npm install`
- After npm finishes, run the gulp command to build the router file `gulp buildRouter.dev`
- The angular_1_router.js file will be in your angular2/dist folder.

## Alternatives
This package is out there solely for convenience. You may directly import the router from Angular's npm package. Read more about on https://github.com/angular/angular.js/issues/12926.
