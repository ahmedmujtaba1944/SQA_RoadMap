
# SQA Engineer RoadMap

An **SQA Engineer** ensures software quality by designing, executing, and analyzing tests to identify defects and verify that the product meets requirements. They work closely with development teams to resolve issues, improve processes, and ensure that the final product is reliable, efficient, and user-friendly. Their role is crucial in delivering high-quality software within deadlines.

---


## Index
- Manual Testing
- API Testing
- Perfomance Testing
- Database Testing
- Automation Testing
- Security Testing



## Manual Testing
- Definition of Software Quality Asuurance (SQA)
- Manual Testing and Automation testing
- SDLC and its  phases
- STLC and its  phases
- Quality Asuurance and Quality Control 
- Verification vs Validation
- Static Testing and Dynamic Testing
- artifacts (test deliverables)
    1. Test Plan
    2. Test Case Document
    3. Test Script
    4. Defect Report
    5. Test Execution Report
    6. Test Summary Report
    7. Defect Density Report
    8. Root Cause Analysis Report
    9. Traceability Matrix (RTM)
    10. Risk Assessment Report
    11. Performance Test Report
    12. Security Testing Report
- use case and test case, practice of writing the testcases. 
- Bug Life Cycle 
- Bug Report
- Severity and Priority
- Bug, Defect, Error, Failure
- Bug triage
- Bug Leakage and Bug Release
- Build and release
- Testing Level 
    1. Unit Testing  
    2. Integration Testing  
    3. System Testing  
    4. Acceptance Testing
- Integration Testing
    1. Big Bang Integration Testing 
    2. Incremental Integration Testing 
        - Top-Down Integration Testing 
        - Bottom-Up Integration Testing
        - Sandwich Integration Testing
    3. Stubs and Drivers Integration Testing
- Acceptance Testing
    1. User Acceptance Testing (UAT)
        - Alpha Testing
        - Beta Testing
    3. Contract Acceptance Testing
    3. Regulation Acceptance Testing
- Blackbox Testing and WhiteBox Testing
- Functional Testing and Non-Functional Testing
- Non-Functional Testing
     - Performance Testing
       - Load Testing
       - Stress Testing
       - Scalability Testing
- Smoke Tesitng and Sanity Testing
- Regression Testing and Re-Testing
- Blackbox Testing Techniques
   - Equivalence Partitioning
   - Boundary Value Analysis
   - Decision Table Testing
   - State Transition Testing
   - Use Case Testing
   - Error Guessing
   - Exploratory Testing 
- Usability Testing
- Security Testing
- Compatibility Testing
- Compliance Testing

## DataBase Testing

### Knowledge of SQL 
#### Database Operations
- **Create Database**: Initializes a new database.
- **Drop Database**: Permanently removes an existing database.

#### Data Definition Language (DDL)
- **Create Table**: Defines a new table with specified columns.
- **Drop Table**: Deletes a table and all its data.
- **Truncate Table**: Removes all rows from a table without deleting the table structure.
- **Alter Table**:
  - **Add**: Introduces a new column to an existing table.
  - **Drop**: Removes a column from a table.
  - **Rename Column**: Changes the name of an existing column.

#### Data Manipulation Language (DML)
- **Select**: Retrieves data from one or more tables.
- **Insert Into Table**: Adds new rows to a table.
- **Delete Row From Table**: Removes specific rows from a table based on conditions.
- **Update Row**: Modifies existing data in a table.

#### Data Query Language (DQL)
- **Select**: Fetches data from the database.
  - **Where**: Filters records that meet specified conditions.
  - **Order By ASC|DESC**: Sorts the result set in ascending or descending order.
  - **Distinct**: Ensures unique results by eliminating duplicate rows.
  - **AND, OR, NOT**: Logical operators used to refine queries.
  - **LIKE**: Searches for a specified pattern in a column.
  - **IN**: Matches any value in a list of specified values.
  - **BETWEEN**: Selects values within a given range.
  - **Aliases**: Provides a temporary name to columns or tables.
  - **Select Top**: Limits the number of rows returned.

#### Aggregate Functions
- **Min**: Returns the smallest value.
- **Max**: Returns the largest value.
- **Sum**: Calculates the total of a numeric column.
- **Avg**: Computes the average of a numeric column.
- **Count**: Counts the number of rows.

#### Grouping and Filtering
- **Group By**: Groups rows sharing a property for aggregate functions.
- **Having**: Filters groups based on aggregate criteria.
- **Exists**: Checks for the existence of rows in a subquery.

#### Joins
- **Inner Join**: Returns records with matching values in both tables.
- **Left Join**: Returns all records from the left table and matching records from the right table.
- **Right Join**: Returns all records from the right table and matching records from the left table.
- **Full Join**: Returns all records when there is a match in either table.
- **Self Join**: Joins a table with itself.
- **Union**: Combines the result sets of two or more queries, removing duplicates.



## Automation Testing

### Selenium Webdriver using TestNG Framework
What is automation testing ?
when we do automation testing ?
Why we need automation testing ?
What is test automation framwork ?
- A testing framwork is a set fo guidlines or rules used for creating and designing test cases.
- A framwork is comprised of a combination of practices and tools that are designed to help QA professiaonls test more effiently.
Types of Framwork ?
- Linear Automation framework.
--- Record-and-playback, the tester records each step such as navigation, user input, or checkpoints, and then plays the script back automatically to conduct the test.  Selenium IDE is the example.
- Module Bases Testing Framework.
--- Based on POM, The framwework divides the entire "Application Under Test" into a number of logical and isolated modules.
- Data Driven Testing Framework
--- file Readers, Data-Driven is a test automation framework which stores test data in a  table or spreadsheet format.
- Hybrid framework is the combination of two or more frameworks. 

Selenium Suits
1. Selenium IDE
- it is record and playback tool, which only supports only firefox. it does not allow conditional statements.
2. Selenium RC Server ( selenium remote control server)
- Selenium RC sends test to a server through which execution is performed.it does not interact with the browser directly due to which the execution of test is very slow.
3. Selenium WebDriver
- it interacts directly with the browser while executing the test. Execution is faster compare to RC.
4. Selenium Grid
- similar architecture as the selenium RS and it used to execute parallel test on multiple environments 


Selenium WebDriver
- it allows you to execute cross-browser tests. 
- it interacts with the broswer directly therefore test execution is fast. 
- WebDriver Interface is the core of the Selenium WebDriver as it has all the required methods and respective nested interfaces defined within it, which helps in simulating user actions inside the browser.
Why do we need RemoteWebDriver class?
-RemoteWebDriver class because it is a fully implemented WebDriver Interface class extended by every BrowserDriver class within the Selenium framework.
RemoteWebdriver class implements the following interfaces:
- WebDriver
- JavaScriptExecutor
- TakesScreenshot
- HasVirtualAuthenticator
- PrintsPage
- HasCapabilities
- Interactive

(Except WebDriver, all other interfaces will be discussed in upcoming posts)

What does Browser Drivers do?
- Selenium provides drivers specific to each browser and without revealing the internal logic of browser functionality, the browser driver interacts with the respective browser by establishing a secure connection.
- These browser drivers are also specific to the language which is used for test case automation like C#, Python, Java, etc.

When a test script is executed with the help of WebDriver, the following tasks are performed in the background:

1) An HTTP request is generated and it is delivered to the browser driver for every Selenium Command
2) The HTTP request is received by the driver through an HTTP server
3) All the steps/instructions to be executed on the browser is decided by an HTTP server
4) The HTTP server then receives the execution status and in turn sends it back to the automation scripts

4) Why do we use Chromium Driver Class?

The ChromeDriver class in Selenium extends the ChromiumDriver class to facilitate shared functionality and code reuse among browsers based on the Chromium engine, such as Google Chrome and Microsoft Edge.

5) What are important methods defined in WebDriver?

 //To close the current browser instance
driver.close();
//To close all the open browser instances
driver.quit();

driver.get("https://google.com");
driver.navigate().to("https://google.com");

Action dragAndDrop = builder.clickAndHold(fromWebElement)
 .moveToElement(toWebElement)
 .release(toWebElement)
 .build().perform();

Basic actions:

click(): Clicks on the element.
sendKeys(String keys): Sends keyboard keys to the element.
clear(): Clears the text input field of the element.

Frame switching:
switchTo().frame(WebElement frameLocator): Switches the focus to a specific frame within the page.

Alert handling:
switchTo().alert(): Switches focus to an alert or confirmation dialog.
accept(), dismiss(), sendKeys(String text): Interact with the alert.


Maven: Maven is a build automation tool that is used to manage the project dependency and the whole projec life cycle.
Pom.xml: pom.xml contains projct information and configuration details used by the Maven build
dependencies: Any library on which a java project is depend on, to run or build is called a dependency. Example: Selenium Jars
