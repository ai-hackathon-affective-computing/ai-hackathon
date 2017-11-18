# BMW Hackathon Webapp

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.6.

## Installation requirements

`yarn` > 0.27.5
`node` > 8.2.1
`angular cli` > 1.2.6

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.2.6.

## Deploy to gh-pages

Build for prod env: `ng build --base-href /hackatnight/ --deploy-url /hackatnight/ --prod`

Push content of `dist` to root(`/`) on `gh-pages` branch.

## Docker development

Build image with `docker build -f Dockerfile-dev -t webapp-starter-dev .` (be sure local `node_modules` is non-existent).
Then run image by executing `docker run -p 4200:4200 webapp-starter-dev` which will watch your changes and expose port `4200`.
In Production run container with docker-compose: `docker-compose up`.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|module`.

## Build

Run `ng build` to build the project or `ng build --prod` for the AOT build. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).
Before running the tests make sure you are serving the app via `ng serve`.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
