# Swag Labs Automation Project

This project contains automated tests for the **Swag Labs** application using **Selenium WebDriver** ,**Java**, and **TestNG**. The tests can be executed both in normal UI mode (with the browser UI visible) and in headless mode (running without the browser UI). Allure is used for generating test reports.

---

## Tech Stack

- **Java**
- **Selenium WebDriver**
- **TestNG**
- **Maven**
- **Allure Reports**
- **Headless Browser Execution**

---

## Getting Started

1.  Clone the repository
git clone https://github.com/SwethaM91/Swag_Labs.git

2. Navigate into the project directory
cd Swag_Labs

3. Install dependencies and build the project
This project requires **Java 11+ and Maven** to build and run the tests.
To install the required dependencies and build the project, run:
mvn clean install

4. Run Tests

    a) **Normal UI Execution:**
    mvn clean test

    b)**Headless Execution:**
    mvn clean test -Dheadless=true
    Headless execution runs the browser in the background without launching the UI — useful for CI/CD or low-resource environments.

5.Reporting 

**Allure Reports** - After test execution, Allure results will be generated under the allure-results/.
 
 To Generate the HTML Report:
  allure serve allure-results - This will automatically open the Allure report in your default browser.

6. Structure
src/test/java – Contains the Test cases and test logic.
