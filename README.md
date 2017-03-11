# ngComponentRouter
> Angular 2 Style Component Router for Angular 1

This is an extract directly built from Angular 2 source code without modification. Adding this as an npm package, because Angular hasn't released an official version yet. 

## Quick Start
For a complete example of how to leverage majority of the features of the router, see https://github.com/duluca/angular1.5-starter. Fork it, create issues with it, otherwise just clone it and use it.

> Note that Angular 1.5.11 is last version of Angular this router and my starter project will work in. However, using this router, Angular Material 1.1.3 and Angular 1.5.11, you can build great production quality applications. The component architecture allows you to follow clean code and SOLID principals, where you can build multi-hundred view apps without your code architecture collapsing under its own weight. Meanwhile you'll be introduced to concepts that form the basis of Angular 2, while leveraging your Angular 1.x skills. If you're looking for a 3-5+ year solution, I highly recommend you start with Angular 2, as that is the foundational framework that'll be supported for Angular v.Next beyond Angular 2.

For more usage examples of the router and an alternate code architecture, check out https://github.com/brandonroberts/angularjs-component-router.

## Based on Angular 2 Commit
03627aa84d90f7f1d8d62f160997b783fdf9eaa4

## Procedure of Extraction
As discussed on https://github.com/angular/angular.js/issues/12926.

- Install gulp globally `npm install -g gulp@latest`
- Clone the angular 2 repo: `git clone git@github.com:angular/angular.git angular2`
- Go into the angular2 directory and install the dependencies `cd angular2` and `npm install`
- After npm finishes, run the gulp command to build the router file `gulp buildRouter.dev`
- The angular_1_router.js file will be in your angular2/dist folder.

## Changes applied
- Replaced unnecessary arrow function on line 3165: config = angular.extend({}, config, { loader: $injector.invoke(loader) });

## Alternatives
This package is out there solely for convenience. You may directly import the router from Angular's npm package. Read more about on https://github.com/angular/angular.js/issues/12926.
