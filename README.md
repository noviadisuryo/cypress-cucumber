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

## Vital Dependency

```bash
Silakan google untuk panduan instalasinya

# Cypress 10 spec bundler
@bahmutov/cypress-esbuild-preprocessor

# Cypress 10 cucumber integrator
@badeball/cypress-cucumber-preprocessor

# Generate allure report from test result
allure-commandline

#Allure reporter for mocha
mocha-allure-reporter
```

## How to Run the Test
```bash
# run test di cmd (headless)
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