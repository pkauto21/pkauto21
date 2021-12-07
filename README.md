Requirement for Test 2
---
1.Implement a test to verify the following user journey
2.Login to https://www.saucedemo.com/ using the "standard_user" account
3.Sort the products by Price (high to low)
4.Add the cheapest & the 2nd costliest products to your basket
5.Open the basket
6.Checkout
7.Enter details and Finish the purchase

Instructions and deliverables
---
Design and implement an extensible test framework to run and verify the above user journey. This should incorporate the best practices of the tooling you chose, and will be reviewed against extensibility and clean code.
Writing the tests Use Java(Selenium) or Javascript(Cypress or Playwright)
We don't expect every single aspect of the journey to be thoroughly tested, but would expect to see some set of scenarios tested
A README.md file explaining the framework briefly and how to run the tests, what you need installed
Pushed to GitHub for review


Git Repo Cloning
---
```bash
## clone this repo to a local directory
git clone https://github.com/pkauto21/GlobalTest2-cypress.git

## cd into the cloned repo
cd exercise2-cypress

## install the node_modules
npm install

## start the local webserver
npm start
```

The `npm start` script will spawn a webserver on port `8080` which hosts the Kitchen Sink App.

You can verify this by opening your browser and navigating to: [`http://localhost:8080`](http://localhost:8080)

We are now ready to run Cypress tests.

Run Cypress Test locally
---
```bash
## launch the cypress test runner
npm run test
```
