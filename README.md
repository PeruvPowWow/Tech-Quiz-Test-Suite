# Tech-Quiz-Test-Suite

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

A simple and interactive quiz application that tests your Python knowledge. This project highlights the use of Cypress for both component and end-to-end (e2e) testing. Users can select from four multiple-choice answers and view their score upon completion of the quiz.

Test Demo Video - 

## Description

This project is designed as a Python quiz with multiple-choice questions. It also serves as a demonstration of component and e2e testing using Cypress. The testing setup allows for visual feedback on each test's success or failure, helping to verify the application's functionality.

## Features

- Interactive quiz with multiple-choice questions.
- Real-time score display upon quiz completion.
- Cypress-based component and e2e testing suite.
- Tests provide visual feedback for each pass/fail result.

## Changes Made
- Added Cypress tests to validate UI components and end-to-end interactions.
- Enhanced UI for better user experience and intuitive navigation.
- Implemented a scoring system for users to view their quiz performance.

## How to Install

These steps are used to install and start the application:

1. Clone the Repository:
``bash``
git clone git@github.com:Runnerrupert/Quiz-Testing.git
``bash``

2. Navigate to the Project Directory:
``bash``
cd your-repository
``bash``

3. Install Dependencies:
``bash ``
npm install
``bash``

4. Build Application:
``bash``
npm run build
``bash``

5. Start the Application:
``bash``
npm run start:dev
``bash``

6. Check the webpage with this URL:
``bash``
http://localhost:3001
``bash``

## Usage

Start Cypress for Component Testing:
``bash``
npm run cypress
``bash``

- You will be given two options, E2E Testing and Component Testing .
- Select Component Testing.
- Choose whichever browser you desire.
- Select "Quiz" under cypress\component
- Each test will run and you will see a corrisponding result, success or failure.
- You can also view each test by selecting each respectively.

Start Cypress for E2E Testing:

You will need two terminals open for end to end testing.

In the first console, run this command:
``bash``
npm run start:dev
``bash``

In the second console, run this command:
``bash``
npm run cypress
``bash``

- Leave the server running in http://localhost:3001. This is needed for E2E Testing.
- Within the Cypress GUI, select E2E Testing.
- Choose whichever browser you desire.
- Select "Quiz" under cypress\component
- Each test will run and you will see a corrisponding result, success or failure.
- You can also view each test by selecting each respectively.

## License

For more information about the MIT license, this will be the link to use https://memgraph.com/blog/what-is-mit-license

For a better understanding, I give you permission to use, copy, modify, distribute and sell copies at your own discretion.

## Future Improvements

- Add more quiz questions to increase engagement.
- Implement a timer for each question to add a challenge.
- Save quiz scores using local storage or a database for user tracking.
- Improve accessibility with better screen reader support and keyboard navigation.

## Conclusion

This Python quiz project not only offers an engaging way to test programming knowledge but also serves as a practical demonstration of automated testing with Cypress. The repository showcases how testing can be effectively integrated into development workflows for reliable software delivery.


## Questions

My Github: https://github.com/PeruvPowWow

My Email Address: pedro.chipana94@gmail.com

You can contact me using my Github link or via Email if you have any questions about Tech-Quiz-Test-Suite

--