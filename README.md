# Next.js 15 App Directory Bug: Unexpected Behavior with Dynamic Routing and Data Fetching

This repository demonstrates an unexpected behavior encountered in Next.js 15's App Directory when combining dynamic routing and data fetching.  A simple application that fetches data and displays it dynamically shows inconsistent behavior.

## Bug Description

The issue involves a seemingly straightforward setup: a dynamic route fetching data and rendering it on the page.  Under certain conditions (as yet undefined), the data fetching either fails or produces unexpected results.

## Steps to Reproduce

1. Clone this repository.
2. Navigate to the project directory in your terminal.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to start the development server.
5. Observe the unexpected behavior when navigating to dynamic routes.

## Expected Behavior

The application should consistently and correctly fetch and display the expected data for each dynamic route.

## Actual Behavior

The application exhibits inconsistent behavior, sometimes failing to fetch data, displaying incorrect data, or throwing errors.

## Solution

The solution involves adjustments to how the data is fetched and handled within the app directory. The `bugSolution.js` file shows a corrected version that addresses the inconsistent behavior.