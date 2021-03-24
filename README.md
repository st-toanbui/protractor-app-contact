# Contacts App Starter for E2E Testing

This project was generated with [Angular CLI](https://github.com/angular/angular-cli)

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

## Steps Install

###### 1. Remove old node by:
> sudo rm -rf ~/.npm ~/.nvm ~/node_modules ~/.node-gyp ~/.npmrc ~/.node_repl_history<br/>
> sudo rm -rf /usr/local/bin/npm /usr/local/bin/node-debug /usr/local/bin/node /usr/local/bin/node-gyp<br/>
> sudo rm -rf /usr/local/share/man/man1/node* /usr/local/share/man/man1/npm*<br/>
> sudo rm -rf /usr/local/include/node /usr/local/include/node_modules<br/>
> sudo rm -rf /usr/local/lib/node /usr/local/lib/node_modules /usr/local/lib/dtrace/node.d<br/>
> sudo rm -rf /opt/local/include/node /opt/local/bin/node /opt/local/lib/node<br/>
> sudo rm -rf /usr/local/share/doc/node<br/>
> sudo rm -rf /usr/local/share/systemtap/tapset/node.stp<br/>

###### 2. Install Node v10.13.0 via link https://nodejs.org/download/release/
###### 3. Install Angular CLI: npm install -g angular-cli@10.2.2
###### 4. Update npm: npm i -g updates
###### 5. Set permission folder: sudo chown -R $USER /usr/local/lib/node_modules
###### 6. ng new protractor-e2e-testing
###### 7. Delete all file of protractor-e2e-testing project without e2e folder
###### 8. Copy all file of protractor-app-contact project without e2e folder and paste to protractor-e2e-testing
###### 9. npm install
###### 10. Open file tsconfig.json and edit "target" : "es2018" to "es2017"



