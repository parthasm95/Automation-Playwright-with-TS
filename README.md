# Automation-Playwright-with-TS
This repo contains framework and Tests with Playwright Tool using TypeScript.


## Setup and Useful Commands : 
### Installing Playwright
npx init playwright@latest

### Add typescript dependency
npm install typescript --save-dev

### intialize TypeScript
npx tsc --init
(update target to "ES6" in tsconfig.json)

### Run Test
npx playwright test 
(Default run mode is headless)

### Open HTML Test Report
npx playwright show-report  

### Run test in headed Mode
npx playwright test --headed 

### Run test in headed Mode on specific browser
npx playwright test --headed --project=chromium

### Run Test in UI mode
npx playwright test --ui  

