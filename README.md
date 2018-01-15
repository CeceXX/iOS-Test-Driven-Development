# iOS Test Driven Development

Example project from a iOS TDD workshop.

## Introduction

* Use unit tests to manage the complexity of larger iOS projects.
* Tests are a safety net against the introduction of bugs.
* Applications that are written using TDD only contain code that is necessary to solve the problem.
* It is very difficult and time consuming to test all the features of big apps by hand (computers are much faster than humans).

## Your first unit test
* Unit tests act like a robot which tests the code for you.
* They execute the code without navigating to the screen with the feature to test.
* You write tests with different input data and let the computer test your code.

## Unit test file
* It's a good practice to have a test case for each class in the main target.
* Every test case needs to import the `XCTest` framework (it defines the `XCTestCase` class and test assertions).
* `@testablle import FirstDemo` imports your main app module.
* `setUp` is called before the invocation of each test method in the `XCTestCase` test class. 
* The `tearDown()` method runs last.
* The `measure` closure runs 10 times and calculates the average duration of that portion of the code (performance tests).
