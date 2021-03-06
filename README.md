## Progressive Web Applications (PWA): Budget Tracker

### Description

*Giving users a fast and easy way to track their money is important, but allowing them to access that information at any time is even more important. Having offline functionality is paramount to the success of an application that handles users’ financial information*

## Installation

Installation is a process of installing the dependencies required.
Intialize node package manager and then run the following commands;  
```script
npm install
```  


## Usage

 In order to use the application locallaly, Run the following command:  
```script
npm start
```  


### App Screenshot

Homepage:

![Homepage](./assets/Homepage.png)

Offline Transaction:

![offline](./assets/offlinesavetransaction.png)

Online Upload:

![backonline](./assets/Backonline.png)

Instal app:
![PWA](./assets/BudgetTrackerpwa.png)

### App Deployed to Heroku

https://quiet-shore-29525.herokuapp.com/


### Application Functionalities

- The ability to enter deposits offline.
- The ability to enter expenses offline.
- Offline entries should be added to the tracker when the application is brought back online

### User Story

```text
AS AN avid traveler
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling 
```

### Acceptance Criteria

```text
GIVEN a budget tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```