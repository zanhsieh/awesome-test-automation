# JavaScript test automation 

A comprehensive curated list of JavaScript test automation frameworks, tools, libraries and software to help software engineers easily bootstrap test automation on JavaScript.

[![Have questions\issues\problems, join the chat at https://gitter.im/atinfo/awesome-test-automation](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/atinfo/awesome-test-automation)

Table of content:

- [xUnit frameworks](#xunit-frameworks)
- [TDD \ ATTD \ BDD](#tdd--atdd--bdd)
- [Code Analysis](#code-analysis)
- [Web UI test automation](#web-ui-test-automation)
- [Mobile test automation](#mobile-test-automation)
- [Windows UI test automation](#windows-ui-test-automation)
- [Unix \ Linux UI test automation](#unix--linux-ui-test-automation)
- [MacOS UI test automation](#macos-ui-test-automation)
- [Virtual environments](#virtual-environments)
- [Performance & stress & load](#performance--stress--load)
- [Security checking](#security-checking)
- [Continuous Integration](#continuous-integration)
- [Reporting](#reporting)
- [Documentation generation](#documentation-generation)
- [Editors, IDE and consoles](#editors-ide-consoles)
- [Useful libs](#useful-libs)

Also:

- [Resources](#resources)
- [Other Awesome Test Automation Lists](#other-awesome-test-automation-lists)
- [Contributing](#contributing)

---

## xUnit frameworks

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## TDD \ ATDD \ BDD

- BDD/TDD
    * [WebdriverIO](http://webdriver.io/) - Nodejs webdriver bindings implementation, based on JsonWire protocol. Requires selenium server running. Includes promises, extended syntax, asynchronus calls with callbacks etc. Also supports SauceLabs, BrowserStack and many other online tools.
    * [WebdriverJS](https://code.google.com/p/selenium/wiki/WebDriverJs) - webdriver nodejs implemetations from authors of selenium, includes all basic features and commands.
    * [MochaJS](http://mochajs.org/) - feature-rich JavaScript test framework running on node.js and the browser.
    * [Intern](https://theintern.github.io/) - is a complete test stack for JavaScript designed to help you write and run consistent, high-quality test cases for your JavaScript libraries and applications. It can be used to test any JavaScript code. Its functional testing capabilities can even be used to test non-JavaScript Web and mobile apps, if you really want.
    * [CodeceptJS](http://codecept.io/) - Modern era acceptance testing for NodeJS
- TDD
    * [Karma](http://mochajs.org/) - test runner for making TDD much easier by pre-build test envitronments.
- BDD
    * [Jasmine](http://jasmine.github.io/) - Behavior Driven Development testing framework for JavaScript. It does not rely on browsers, DOM, or any JavaScript framework. Thus it's suited for websites, Node.js projects, or anywhere that JavaScript can run.

## Mock frameworks
* [Sinon.JS](http://sinonjs.org/) - Standalone test spies, stubs and mocks for JavaScript.
No dependencies, works with any unit testing framework.
* [JSMockito](http://jsmockito.org/) - JsMockito is a JavaScript stub/mock framework heavily inspired by java's Mockito.
* [apimocker](https://github.com/gstroup/apimocker) - This is a node.js module to run a simple http server, which can serve up mock service responses. Responses can be JSON or XML to simulate REST or SOAP services.

## Code analysis 
* [HintJS](http://jshint.com/) - Community driving js code analysis tool supported by twitter, facebook, wiki, jquery, mozilla, yahoo and others.
* [JsLint](http://www.jslint.com/) - JavaScript syntax checker and validator.

## Web UI test automation
* [WebdriverIO](http://webdriver.io/) - Nodejs webdriver bindings implementation, based on JsonWire protocol. Requires selenium server running. Includes promises, extended syntax, asynchronus calls with callbacks etc. Also supports SauceLabs, BrowserStack and many other online tools.
* [WebdriverJS](https://code.google.com/p/selenium/wiki/WebDriverJs) - webdriver nodejs implemetations from authors of selenium, includes all basic features and commands.
* [Protractor](http://angular.github.io/protractor/) - End-to-end test framework for AngularJS applications.
* [Nightwatch.js](http://nightwatchjs.org/) - Easy to use Node.js based End-to-End (E2E) testing solution for browser based apps and websites.
* [Dalek.js](http://dalekjs.com/) - Automated cross browser testing with JavaScript.
* [Nemo](https://github.com/paypal/nemo) - Nemo provides a simple way to add selenium automation to your NodeJS web projects. With a powerful configuration ability provided by krakenjs/confit, and plugin architecture, Nemo is flexible enough to handle any browser/device automation need.
* [Frisby](https://github.com/vlucas/frisby) - Is a REST API testing framework built on node.js and Jasmine that makes testing API endpoints easy, fast, and fun.

## Mobile test automation
* [WebdriverIO's Appium implementation](http://webdriver.io/api/appium/backgroundApp.html) - nodejs bindings implemeting Appium commands.

## Windows UI test automation 

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Unix \ Linux UI test automation 

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## MacOS UI test automation 

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Virtual environments

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Performance & stress & load

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Security checking

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Continuous Integration
* [Strider CD](https://github.com/Strider-CD/strider) - Open Source Continuous Deployment / Continuous Integration platform written in NodeJS.
* [Gulp](http://gulpjs.com/) - Streaming building system/task runner in nodejs. Based on streaming data flow conception (https://github.com/substack/stream-handbook).
* [Grunt](http://gruntjs.com/) - Streaming building system/task runner in nodejs. Can't do anything without plugins, but there are many of them for all kinds of purposes.

## Reporting
* [Istanbul](https://github.com/gotwarlost/istanbul) - JS coverage tool for unit tests, server side functional tests and browser tests.
* [Blanket](http://blanketjs.org/) - JavaScript code coverage library that works both in-browser and with nodejs.

## Documentation generation

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)

## Editors, IDE, consoles
* [WebStorm](https://www.jetbrains.com/webstorm/) - PhpStorm without php support. One of thee most powerfull JS/HTML IDE.
* [Brackets](http://brackets.io/) - Open source newly released IDE for JS/HTML from Adobe. 
* [Komodo](http://komodoide.com/) - Cross platform IDE for multiple languages, strongly supporting JS.
* [Cloud9](https://c9.io/) - Cloud based nodejs IDE supporting multiple features, eg. pair programming, preview in a new browser, built-in image editor, terminal and many others
* [Visual Studio Code](https://code.visualstudio.com/) - Cross platform editor from Microsoft, with integrated Node.js debugger and hooks for taskrunners such as Gulp
* [Atom](https://atom.io) - Full-featured, right out of the box text editor that's modern, approachable, yet hackable to the core from Github

## Useful libs

[Contribute to this section](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)


# Resources
Where to discover new libraries, information, tools, etc.

## Websites

* [automated-testing.info](http://automated-testing.info) - Test automation community
* [atinfo.github.io/at.info-knowledge-base](http://atinfo.github.io/at.info-knowledge-base/)  - Knowledge base for test automation examples on different tools and technologies

# Other Awesome Test Automation Lists

* [python test automation](https://github.com/atinfo/awesome-test-automation/blob/master/python-test-automation.md)
* [java test automation](https://github.com/atinfo/awesome-test-automation/blob/master/java-test-automation.md)
* [ruby test automation](https://github.com/atinfo/awesome-test-automation/blob/master/ruby-test-automation.md)
* [c# test automation](https://github.com/atinfo/awesome-test-automation/blob/master/c%23-test-automation.md)
* [php test automation](https://github.com/atinfo/awesome-test-automation/blob/master/php-test-automation.md)
* [javascript test automation](https://github.com/atinfo/awesome-test-automation/blob/master/javascript-test-automation.md)
* [test automation and software testing as services](https://github.com/atinfo/awesome-test-automation/blob/master/automation-and-testing-as-service.md)
* [mobile, tablet and tv test automation](https://github.com/atinfo/awesome-test-automation/blob/master/mobile-test-automation.md)

# [Contributing](https://github.com/atinfo/awesome-test-automation/blob/master/CONTRIBUTING.md)
Your contributions are always welcome!
