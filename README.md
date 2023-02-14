# Bill Manager - React.js, Redux, Saga, Chart.js

- - -

### A demo app to illustrate various features of a react.js application:

- - -
## Problem Statement:

Adithya owns a car wash business and needs help to manage various bills from his vendors. Need to build an application to help Adithya manage his monthly bills. The bill manager should show a bill dashboard (list of bills) with the total monthly billed amount.


## Functional requirements:

- The user must be able to manually add, edit and remove bills. (update the state locally)
- The user must be able to filter bills by category. (category filter dropdown)
- Draw a time-series chart of the monthly billing cycle.


## Screens

1. **Overview Page** - Shows monthly bills in a graph


2. **Create/Edit Bill Screen** - Create or edit bills on this screen using a simple form


3. **List all Bills Screen** - Create or edit bills on this screen using a simple form


## LocalStorage Data Storage

We are storing the data in localstorage to persist data in case of page refresh.

One bill object looks like following:

```
{
"id": 1,
"description": "Dominoes",
"category": "FoodNDining",
"amount": "430",
"date": "01-02-2020"
}
```