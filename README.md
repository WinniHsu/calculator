[![Board Status](https://dev.azure.com/WinnieHsu0417/a3696ce3-7d95-43ee-8dc0-939667cebf1c/9e40783a-d701-45bd-8057-4d135b4898ce/_apis/work/boardbadge/07d935ad-2e2b-4d33-942b-4820257dafde)](https://dev.azure.com/WinnieHsu0417/a3696ce3-7d95-43ee-8dc0-939667cebf1c/_boards/board/t/9e40783a-d701-45bd-8057-4d135b4898ce/Microsoft.RequirementCategory)
Calculator.js: a node.js Demonstration Project
==============================================
An example node.js project, including tests with mocha, that behaves like
a pocket calculator.

The project contains a simple node.js application that exposes REST APIs
to perform arithmetic on integers, and provides a test suite with mocha
and chai.  The `mocha-junit-reporters` package is included to provide XML
output that can be presented in a continuous integration tool like
[Azure DevOps](https://azure.com/devops).

To build, simply:

1. Runs `npm install` to install dependencies.
2. Runs `npm test` to run Mocha and execute the unit tests.

