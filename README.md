# GermanyIsCalling
It is a automation assignment which is for GermnayIsCalling and it is for login and register functionality including valid and Invalid  test cases. it is Build in purely Selenium with java and for managing test execution used TestNG which have report genration also after execution.


## Objective
It is a Selenium with java project to test the login functionality with valid and invalid data to test it is working as per expectations or not and after execution execution report is also genrated by TestNG(used to manage test cases).
## Project Setup
* Open the eclipse IDE
* Create Maven Project
* Add the dependencies like (Selenium,TestNG) into pom.xml file
* Create package in src/test/java
* Create class in package(automation).{class are actual test scripts}
* Create testing.xml file in project by right click on project and choose convert to TestNG in TestNG.
  
### Prerequisites
* Eclipse IDE
* Dependencies in POM file
* Test cases
* Browser{Chrome)
* User credentials
* TestNG

### Dependencies
* Selenium
* TestNG

## Test Execution Steps
After writing the script save your code and right click to choose and RUN
* IF you want to run particular then go to that file and right click and choose RUN as TestNG Test.
* IF you want to run overall suite then go to testing.xml file and right click and choose RUN as TestNG suite.

## Tests

### 1. Successful Login Test

**Description:** For successful login test it will be login and redirect to homepage.

### 2. Unsuccessful Login Test

**Description:**  for unsuccessful login test it will show alert and i have used assertion to compare that alert inner text to actual text.

## Test Execution Report
  # After execution to see report:
  * Go to test output folder and find index.html file
  * Right click onto the file and choose open with web browser in open
  * Avble to see report in browser
  * 

## Comments in Code

I have put enough comment in eaach step to understand what it is doing and what we will get.
