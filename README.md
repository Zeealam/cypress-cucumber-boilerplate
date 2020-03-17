# Cypress with Cucumber BDD and Amplify console ß CI/CD Pipeline

# Dependencies:
1. npm install
2. npm link
3. npm link cypress-cucumber-preprocessor

# set host/ baseurl
1. go to cypress.json file
2. set baseurl

# Dashboard execution:
1. Go to project root, 
2. npx cypress open
3. click specific feature file [executionwillstart]

# cmmd line Execution:
1. npm run test:mochawesomereport
2. npm run test:allurereport
3. npm run generatereport

# Visual Test
1. npm run test:visual-base
2. npm run test:visual-actual
3. Snapshots will be generated in 'snapshots' folder

# Reports:
1. Reports will be generated in 'mochawesomereport-report' folder - command line execution only
  
   ex: npm run test:mochawesomereport

2. Allure reports: 
    a. npm run test:allurereport
    b. npm run generatereport






