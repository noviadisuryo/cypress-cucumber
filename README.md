# Cypress 10.x.x + Cucumber + Allure

Simpel project dengan cypress 10.x.x menggunakan cucumber BDD dan allure sebagai test reporter.

## Instalasi

```bash
# create package .json
npm init

# install Cypress
npm install cypress --save-dev

# buka cypress setup
npx cypress run
```

## Test Case

```bash
Lokasi testcase dan dependensinya

# Gherkin feature file
cypress/e2e/feature

# Step Definitions
cypress/e2e/step_definitions
```

## Penggunaan
```bash
# run test di cmd
npx cypress run

# run test dengan browser tertentu
npx cypress run --browser chrome
npx cypress run --browser firefox

# run test non headless
npx cypress run --headed

# run test lewat cypress UI
npm cypress open

# run test menggunakan allure report
npm run test:allure
```

## Sumber 

[Joan Media - Cypress 10 Installation](https://www.youtube.com/watch?v=uIX8nHBfo-o) 

[Joan Media - Cypress with Cucumber](https://youtu.be/FlQ9Carxeds)

[Sailaja Kandula](https://youtu.be/_1B4oB1QHtM)