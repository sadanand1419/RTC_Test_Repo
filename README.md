Assignment:
Write automated tests using Playwright and embed both coding and test automation best practices in your automation suite.
Application under test: https://www.saucedemo.com/
Scenarios to be automated
Verify the sorting order displayed for Z-A on the “All Items” page.
Verify the price order (high-low) displayed on the “All Items” page.

Prerequisites:
Node.js and npm: Ensure you have Node.js and npm installed on your system. You can download them from the official Node.js website (https://nodejs.org/).
Visual Studio: Download and install Visual Studio from the official Microsoft website (https://visualstudio.microsoft.com/). Community Edition is sufficient for most development needs.
Playwright: Install Playwright globally using npm:npm install -g playwright

Project Setup:

Create a New Project: Open Visual Studio and create a new JavaScript project.
Install Playwright Dependencies: Open a terminal in your project directory and install Playwright dependencies for your chosen browser (Chromium Version 132.0.2957.127 (Official build) (64-bit), Firefox, WebKit) : npm install playwright @playwright/test
Create a Test File (e.g., rtcamp.spec.js): Create a JavaScript file.
Run through terminal : 
1. npx playwright test rtcamp.spec.js --project=chromium --headed
2. nps playwright show-report
