# Universal Angular Application

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.2.

## Getting started

```shell
git clone https://github.com/enten/angular-universal my-project
cd my-project
ng serve
ng build
node ./dist/app/server/main.js
```

This starter kit contains all the minimal tooling and configuration you need to kick off your next [Angular Universal](https://angular.io/guide/universal) project.

It suggests an universal approach to build an universal application for both browser and server in same time.

The main difference from others universal starter kits is the number of commands needed to develop and build your universal application.

### Commands

* `ng build` - Building bundles for both browser and server platforms in [same compilation](https://github.com/webpack/webpack/tree/master/examples/multi-compiler) ;
* `ng serve` - Running universal dev server with [HMR](https://webpack.js.org/concepts/hot-module-replacement/) on browser and server sides ;
* `ng serve -c spa` - Running universal dev server with SSR disabled for angular routes only.

### Branches

<table>
  <thead>
    <th>Branch</th>
    <th></th>
    <th></th>
  </thead>
  <tbody>
    <tr>
      <td><a href="https://github.com/enten/angular-universal/tree/material">material</a></td>
      <td><img alt="Preview of branch material" src="https://i.imgur.com/khXkDnA.png"></td>
      <td><pre></code>git clone https://github.com/enten/angular-universal \
  -b material my-project
cd my-project
npm install
npm start</code></pre></td>
    </tr>
    <tr>
      <td><a href="https://github.com/enten/angular-universal/tree/toh">toh</a></td>
      <td><img alt="Preview of branch toh" src="https://i.imgur.com/T2TzP7t.png"></td>
      <td><pre></code>git clone https://github.com/enten/angular-universal \
  -b toh my-project
cd my-project
npm install
npm start</code></pre></td>
    </tr>
    <tr>
      <td><a href="https://github.com/enten/angular-universal/tree/i18n">i18n</a></td>
      <td><img alt="Preview of branch i18n" src="https://i.imgur.com/6h2dkk7.png"></td>
      <td><pre></code>git clone https://github.com/enten/angular-universal \
  -b i18n my-project
cd my-project
npm install
npm start</code></pre></td>
    </tr>
  </tbody>
</table>

## Development server

Run `ng serve` to start universal dev server. Navigate to [http://localhost:4000/](http://localhost:4000/).

The app will automatically hot-reload on server and browser sides if you change any of the source files.

The full compilation will automatically restart if a hot chunk can't be applied on server side.

Tip: run `ng serve -c spa` to disable server side rendering of routes only.

[![Universal dev server with ng-udkc](https://i.imgur.com/vPzCMBk.gif)](https://imgur.com/a/cpbhHgg)

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/app` directory.

Run `ng build --prod` for a production build.

Run `node dist/app/server/main.js` to start application built.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
