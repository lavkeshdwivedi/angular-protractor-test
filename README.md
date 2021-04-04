##Setup

##Use npm to install Protractor globally with:

npm install -g protractor

This will install two command line tools, protractor and webdriver-manager. Try running protractor --version to make sure it's working.

##The webdriver-manager is a helper tool to easily get an instance of a Selenium Server running. Use it to download the necessary binaries with:

webdriver-manager update

##Now start up a server with:

webdriver-manager start

This will start up a Selenium Server and will output a bunch of info logs. Your Protractor test will send requests to this server to control a local browser. You can see information about the status of the server at http://localhost:4444/wd/hub.

##Install the needed dependencies
npm install --save-dev @types/{chai,cucumber} chai cucumber protractor-cucumber-framework

##Chai
Cucumber is a testing framework which doesn't come with an assertion library like Jasmine does, so we need to install one–chai in this article.

##To Run
ng e2e

##More details:
https://www.amadousall.com/angular-e2e-with-cucumber/
