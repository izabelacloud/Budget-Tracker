# Budget Tracker

![Github licence](http://img.shields.io/badge/license-MIT-blue.svg)

## Description

The Budget Tracker is an application that allows to track the budget and leverages offline access and functionality where the user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. This application is using MongoDB / NoSQL along with Express.js and Mongoose.

## Table of Contents

* [Deployed Application](#deployed-application)
* [User Story](#user-story)
* [Usage](#usage)
* [Local Setup](#local-setup)
* [License](#license)
* [Contributing](#contributing)
* [Questions](#questions)

## Deployed Application

[https://budget-tracker-web-production.up.railway.app](https://budget-tracker-web-production.up.railway.app)

## User Story

AS AN avid traveler<br />
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection<br />
SO THAT my account balance is accurate when I am traveling<br />

GIVEN a budget tracker without an internet connection<br />
WHEN the user inputs an expense or deposit<br />
THEN they will receive a notification that they have added an expense or deposit<br />
WHEN the user reestablishes an internet connection<br />
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated<br />

## Usage

This application allows to track the budget and leverages offline access and functionality where the user will be able to add expenses and deposits to their budget with or without a connection.

## Local Setup

This app requires Node.js 18+ and a MongoDB database.

1. Install dependencies: `npm install`
2. Start MongoDB locally (e.g. `brew services start mongodb/brew/mongodb-community`)
3. Optionally set `MONGODB_URI` in a `.env` file if not using the default `mongodb://localhost/budget`
4. Start the server: `npm start` (or `npm run watch` for auto-reload during development)
5. Visit `http://localhost:3001`

## License

This project is licensed under the MIT.

## Contributing

Izabela Petrovicova

## Questions

If you have any questions about the repository, contact me directly at [i.petrovicova@gmail.com](mailto:i.petrovicova@gmail.com). You can find more of my work at [github.com/izabelacloud](https://github.com/izabelacloud).
