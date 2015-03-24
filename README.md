## Protractor showcase

Protractor is an end-to-end test framework. 

Protractor runs tests against your application running in a real browser, 
interacting with it as a user would.

### Setup

    > npm init
    > npm install protractor --save
    > protractor --version # Version 2.0.0

### Run the example test

1. open a new shell and lunch webdriver-manager

        > webdriver-manager start # start up a server at http://localhost:4444/wd/hub

2. return to the previous shell and run:

        > node_modules/.bin/protractor node_modules/protractor/example/conf.js

### Issues

1. If you get the message `[launcher] Error: Error: Could not find chromedriver at ....` you should install `chromedriver` module and then add the parameter `chromeDriver: ../../../node_modules/chromedriver/bin/chromedriver` in `protractor/example/conf.js`

<!-- 
### References:
Julie Ralph End to End Angular Testing with Protractor.mp4 
-->
