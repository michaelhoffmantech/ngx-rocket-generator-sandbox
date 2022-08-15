# ngx-rocket-generator-sandbox
Sandbox to generate projects with generator ngx rocket

## Installation

Ran the command:

```
npm install -g generator-ngx-rocket
```

## Create New Application

Ran the command from the command line:

```
ngx new
```

Then went through the new project wizard and selected/entered the following:

1. Entered the project name as HelloWorld
1. Selected Web App
  1. Other options included Mobile app (using Cordova) and Desktop app (using Electron)
1. Selected Angular Material as the UI framework
  1. Other options included Ionic for mobile-oriented and Bootstrap for website-oriented
1. Selected side menu with split panels, app-oriented
  1. Other option was Simple responsive header bar website-oriented
1. I left the default feature selections: Progressive Web App, Authentication, Lazy loading and End-to-end tests with Cypress
  1. Other option was Analytics with Angulartics2
1. Kept default language as en-US
1. Additional tools included:
  1. Prettier for automatic code formatting (selected)
  1. Hads (markdown-based doc system) (selected)
  1. Compodoc (Angular doc generator)
  1. Jest (Jasmine test replacement)
  1. Protractor (deprecated)
  1. Puppeteer (embedded Chrome for testing)
1. Additional libraries included:
  1. Lodash (collection and general utilities) (selected)
  1. Ramda (Lodash FP alternative)
  1. Moment.js (date management) (selected)
  1. Date-fns (Moment FP alternative)
1. Automatic deployment
  1. No Deploy (selected)
  1. Firebase
  1. Azure
  1. Now
  1. Netlify
  1. GitHub Pages
  1. Amazon

The project then built successfully and the following tasks were available:

* $ npm start: start dev server with live reload on http://localhost:4200
* $ npm run build: build web app for production
* $ npm test: run unit tests in watch mode for TDD
* $ npm run test:ci: lint code and run units tests with coverage
* $ npm run e2e: launch e2e tests
* $ npm run docs: show docs and coding guides
* $ npm run prettier: format your code automatically

## Run Web Application

After creating the HelloWorld application, I ran the following command:

```
npm start
```

Server started and was available at: http://localhost:4200/

Logged in with admin/admin
