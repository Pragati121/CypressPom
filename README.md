I have implemented Pom , Custom Command  ,Allure reports , Api verification in this project 
For creating a project of cypress i have used following commands -1.npm init 2.npm install cypress@9.7.0 3.npx cypress open 4.npx cypress run
for the x-path i have run folowing command on the terminal -npm install -D cypress-xpath
for generating the Allure reports i have used these commands-1.npm i -D @shelex/cypress-allure-plugin,Added these plugin in plugins/index.js file.
2.npx cypress run --env allure=true,allureResultsPath=cypress/allure_results and for running the tests i have used -npm test


