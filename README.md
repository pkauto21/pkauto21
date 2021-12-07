
1. Git Repo Cloning

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

2. Run Cypress Test locally
```bash
## launch the cypress test runner
npm run test
```
