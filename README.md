# BrowserStack-Cypress Integration

This example is about integrating cypress v10 test suite with BrowserStack.

Steps:
1. Create Project, npm init
2. Install cypress, save as dev dependancy: npm install cypress --save-dev Ref: https://docs.cypress.io/guides/getting-started/installing-cypress
3. Open the app, npx cypress open 
4. From the Cypress launchpad create an End to end testing configuration //this will provide the cypress structure required for the project. 
5. Choose quick configuration, start e2e testing in chrome or firefox
6. Create a spec.cy.js file add all the scripts here

Cypress project is created now, whenever the file is saved we can see the logs in Cypress dashboard

Integration to BrowserStack, Follow the documentation: https://www.browserstack.com/docs/automate/cypress/integrate-your-test#Cypress_v10
