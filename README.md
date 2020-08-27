# Expedia Hotel Journey
This is a task to Automate the [Expedia Hotel booking system](https://www.expedia.co.uk/Hotels) using Cypress and Cucumber, Please see below for the Test Case that are automated 

## **Test Scenario**: Stay Function

| Test Case Number | Test Case |
|--|--|
|TC001  | Verify that the stay screen contains elements such as Destination, departure Date, Arrival Date, Add Flight, Add Car, Travellers and Search button. |
|TC002|Verify if a user will be able to successfully search with a valid data|
|TC003  | Verify if a user will not be able to book a flight without location |
|TC004  |Verify if a user is able to filter deals  |

Note - These are one of the few to be automated
## Install

1.  clone the repo
2.  `npm install`

## Run tests
**Pretest** - Create a 'reports' folder in cypress folder

 - Run test on UI
```
npx cypress open
```


- Run test on Command Line:

**Note** - Some Scenarios may fail on command line due to website response time  
```
npm run test

```

Run test with tags:  **Tags**  - @e2e @TC001 @TC002 @TC003 @TC004

```
npm run test -e TAGS='e2e'
```


## Technology used:

 - Cypress
 - Cucumber
 - Mochawsome
