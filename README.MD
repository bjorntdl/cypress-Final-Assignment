### How to install NPM packages:

`npm install`

### How to NPM scripts from your project:

``` javascript

npm run cypress:open - launch the UI for executing the tests 
npm run cypress:run:all - execute all tests within the CLI


### How to run Cypress in headless mode:

`npm run cypress:run`

### How to run Cypress in E2E mode 


`npm cypress:run --e2e`

### How to specify particular browser for the Cypress to execute

`npm run cypress:run --browser chrome/firefox/elector/etc`

If `--browser` flag is not specified Cypress will run tests against `Electron` browser by default.


The structure of this project is:
1. "e2e" folder contains all the tests written. In some cases some of the tests are written within the same "it" in order to be more efficient and logical. 
2. "pageObjects" folder contains functions for locating and interacting with the elements the tests intend to run on.
3. "fixtures" folder contains the default "example.json" and another file which i used for creating a class importing content from an external library which i use for testing.
4. I have tried to use the same type of styling/writing code all around as per your request

