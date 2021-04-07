# Budget-Tracker

The budget tracker application provides a tool for tracking financial progress against a budget regardless if the user is on-line or not. 

## User Experience

Every time the user gains or uses funds, they record it in the budget tracker. The budget tracker keeps a running total of the amount of funds in the account. Offline transactions are stored locally and added to the sum once an internet connection is restored making the application more effective by giving the user maximum flexibility of use. 

## Technology Used

The budget tracker is a node.js solution using express, logger, mongoDB and compression packages. The main database is a mongoose database with indexedDB storage utilized while offline. The application is deployed on heroku using mango atlas. 

## Mock Up

![Budget Tracker Image](https://github.com/catherinebshaw/Budget-Tracker/blob/main/public/Budget-trackerSS.png)

## Live Site
[Budget Tracker](https://budget-tracker-cs.herokuapp.com/)
