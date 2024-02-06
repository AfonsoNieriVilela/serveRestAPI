# serveRestAPI
Postman course - api tests with newman and htmlextra

# Bootcamp #01 Qualiters Club
Rest API testing from manual to CI/CD
## What is it
This repository was created for the Rest API Testing Bootcamp.

## Technologies used
- Postman versão web
- node version v18.16.1
- newman v5.3.2
- newman-reporter-html
  
## Documentações
- Technical Analysis: Analysis/
- API doc: [Swagger](https://serverest.dev/#/)
  
## How to set up the environment
- First: install Node on your computer [download](https://nodejs.org/en/download)
- Second: install Newman globally [download](https://www.npmjs.com/package/newman)
```
npm install -g newman
```
- Third: install the reporting dependency (optional) [newman-reporter-html
](https://www.npmjs.com/package/newman-reporter-html)
```
npm install -g newman-reporter-html
```
## How to run the tests
### Using Postman web or desktop
-Import the collection and environment
- Execute the tests manually or automated
### Using newman
- Open the preferred console
- Execute the following command to run the tests
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli
```
- Execute the tests with a report
```
newman run ServeRest.postman_collection.json -e serveRest_env.postman_environment.json -r cli,htmlextra
```
### Report
If you chose to run the tests with the HTMLExtra report, you generated an HTML file with the test results, and to verify the validations

## Contact
- email: afonsovilela.96@gmail.com
- social networks: https://www.linkedin.com/in/afonso-vilela-4195b9190

