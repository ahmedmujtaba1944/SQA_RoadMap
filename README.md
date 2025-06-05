
# SQA Engineer RoadMap
Technical skills
Business acumen 
Soft skills


Technical skills 
1. Basics of programming language ( pick one language do it's basic, oop, problems)
2. Knowledge of source control git, GitHub 
3. Knowledge of database SQL 
4. Technology stack is used in application, able to read log files( able to read exception or errors ), understand stack trace or test api 
5. Knowledge of cloud ( azure, , google cloud) and CI/CD tools ( Jenkins, azure DevOps)
6. Knowledge of testing tools bug management , test case management ( testrail, Jira)
7. Good command over automation practice 
8. Knowledge of Linux commands ( docs, Linux, bash)
9. Understand of mobile, web and api ( do self learning on all stacks)
10. Knowledge of NFRs ( Performance( tools, types), security ( top ten attacks, solution, report), usability, accessibility( special people))
11. Knowledge of software development process ( TDD,BDD).

Automation ( Arrangements (finding the locators and writing in POM/BDD )and , Action, Assertion ( verify the action))
1.Learn basics of programming language ( pick one language do it's basic, oop, problems hacker rank) string reverse, integer reverse, prime number, string palindrome, Hacker rank basic, intermediate problem solving certification ( daily one program)
2. Learn DB queries on hacker rank 
3. Focus on the following tools
 Selenium WebDriver with java for web automation 
 Appium with java for mobile automation 
 Rest assured for API automation 


Tools 
Google page speed insight/ gtmatrix for performance 
BURP/ Acunetix / ZAP for security testing 
Selenium/ cypress/ playwright for web ui automation 
Postman/ rest assured for API automation 
Appium/ espresso for mobile automation 
JMeeter/ load runner for load and stress testing 
Applitools eyes / sikuli for automated visual testing 
Cucumber/ specFlow  for knowledge of BDD 
Test comple/ ranorex /QTP QFT
TestRail / Zephyr for test case management 
Jira/ azure/ Bugzilla for bug management 
Jenkins/ bamboo/ aws/ azure DevOps for CI/CD 

Business acumen ( Domain knowledge)
1. Have customer prospective 
2. Asking and understanding what problem of the customer does the feature solve. 
3. Asking what and why?
4. Understanding risks and opportunities 
5. Can become expert in a domain in less time (flexible)
6. Only then you can uncover the scenarios
Also check the compatible apps for getting more projects knowledge 
Example 
Doctor or patient app 
POS keyboard friendly ( super market )
POS touch screen in restaurants 

Soft skills 
1. Communication ( written, verbal, listening) more listen speak less. 
2. Empathy or positive attitude 
3. Emotional Intelligence ( how to get along and how to handle bullies) 
4. Eager to learn and Share 
5. Time management 
6. Leadership 
7. Being coachable

How to develop those skills 
1. Learn everyday 
2. Read everyday ( ministry of testing, software testinghelp.com, Guru99.com, toolSQA.com)
3. Do online courses ( TAU, Udemy, Lambda test ) 
4. YouTube ( automation step by step, Naveen automation labs, Rahul Shetty, execute automation, SDET) 
5. Internship in good project based companies 
6. Attend meetups and sessions 
7. Follow experts on LinkedIn or Twitter 
8. Participate in open source project 
9. Freelancing 

Careers 
1. Management Track ( associate SQA, SQA, Senior SQA, Lead SQA, Manager SQA Senior Manager SQA, Associate Director, Director, VP) 
2. Individual Contributor Tract 
Automation 
Performance 
Security

Rotation in the Field 
Project management, business analyst, scrum master, consultant, developer, DevOps, designer.


---




# Notes 
---
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

--- 
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

---

## Automation Testing

### Selenium Webdriver using TestNG Framework
What is automation testing ?
when we do automation testing ?
Why we need automation testing ?
What is test automation framwork ?
- A testing framwork is a set fo guidlines or rules used for creating and designing test cases.
- A framwork is comprised of a combination of practices and tools that are designed to help QA professiaonls test more effiently.
#### Types of Framwork ?
1. Linear Automation framework: Record-and-playback, the tester records each step such as navigation, user input, or checkpoints, and then plays the script back automatically to conduct the test.  Selenium IDE is the example.
2. Module Bases Testing Framework: Based on POM, The framwework divides the entire "Application Under Test" into a number of logical and isolated modules.
3. Data Driven Testing Framework: file Readers, Data-Driven is a test automation framework which stores test data in a  table or spreadsheet format.
4. Hybrid framework is the combination of two or more frameworks. 

#### Selenium Suits
1. Selenium IDE: it is record and playback tool, which only supports only firefox. it does not allow conditional statements.
2. Selenium RC Server ( selenium remote control server): Selenium RC sends test to a server through which execution is performed.it does not interact with the browser directly due to which the execution of test is very slow.
3. Selenium WebDriver: it interacts directly with the browser while executing the test. Execution is faster compare to RC.
4. Selenium Grid: similar architecture as the selenium RS and it used to execute parallel test on multiple environments

#### Selenium WebDriver
- it allows you to execute cross-browser tests. 
- it interacts with the broswer directly therefore test execution is fast. 
- WebDriver Interface is the core of the Selenium WebDriver as it has all the required methods and respective nested interfaces defined within it, which helps in simulating user actions inside the browser.


**Maven :** Maven is a build automation tool that is used to manage the project dependency and the whole projec life cycle.
**Pom.xml :"** pom.xml contains projct information and configuration details used by the Maven build
**dependencies :** Any library on which a java project is depend on, to run or build is called a dependency. Example: Selenium Jars

#### Most Common functions:
Find Element : `WebElement element = driver.findElement(By.linkText("read more"));`
Click: `element.click();` (this method clicks on the selected element.)  
GetText: `String txt = element.getText();` (this method retrieves the text of the selected element as a String.)  
Send Keys:`element.sendKeys("text");` (this method sends a sequence of characters or a string to the selected element.)  
Navigate To: `driver.navigate().to("url");` (this method loads a new web page in the existing browser window.)  
Navigate Forward: `driver.navigate().forward();` (this method enables the web browser to click on the forward button in the existing browser window.)  
Navigate Back: `driver.navigate().back();` (this method enables the web browser to click on the back button in the existing browser window.)  
Navigate Refresh:`driver.navigate().refresh();` (this method refreshes the currently open page.)  
Get: `driver.get("url");` (this method loads a new web page in the existing browser window.)  
Get Title:`driver.getTitle();` (this method fetches the title of the current webpage and returns it as a String.)  
Get Current URL:`driver.getCurrentUrl();` (this method fetches the current URL of the web page and returns it as a String.)  
Quit: `driver.quit();` (this method terminates all windows operated by the WebDriver.)  


##### Locators 


#### Page Objet Model:
- Page Object Model (POM) is a desing pattern, that creates Object Repository for Web UI element.
- In Page Object model (POM) all Web Elements and the method that operate on these Web Elements are maintained inside a separate file and page class. A task like verification or assertion  should be separate as part of Test methods in a test class.
- Due to this structure, we create functions bases on logical tasks that we may need to perform multiple types and use these functionals in different tests.
- for example, we can create a function for login and use in a happy case with a login successful assertion and in  a negative case with a login failed assertion.
- Using Page Object Model reduces redundancy in code and it also make test case maintenance very easy.


#### Data Driven Framework
- In data-driven, we separate test inputs in a seprate file and use a fiel reader to get
- the data form that file into our scripts. this provide us with separate repository for data input or outputs. 

#### TestNG
- TestNG is an automation testing framework in which NG stands for "Next Generation" which uses the annotation(@)
- Using TestNG, you can generate a proper report and you cna easily come to know how many test caes are passed, failed and skipped.
- if Follows ATDD approach which stands for Acceptance Test Driven Development Approach.
- it involves writing automated tests from the users perspective and is designed to assert and validate the functionality of the software being developed.

#### @Test Annotation
- @Test is used to tell that the method under it is a test case.
- Since we use annotations in TestNG, we needed to import the packages org.testing.annotation.*
- You may have multiple test cases( therefore, multiple @Test annotations) in a single TestNG file.

#### common attributes
- description: It is the description for the methods 
- Eg: @Test(description = "test method")
- Priority: This command sets the priority of the test methods.
- Eg: @Test(priority  1)

#### Assertions
1. assertEquals
Assert.assertEquals(actual, expected);
Validates if the actual and expected values are the same or not.
2. assertNotEquals
Assert.assertNotEquals(actual,expected,Message);
whenever the expected and actual values match, the assertion fails with an exception and marks the testcase as "failed".
3. assertTrue
Assert.assertTure(condion);
This method asserts if the condition s true or not. if not, then the exception error is thrown.
4. assertNotNull
Assert.assertNotNull(object);
Verifies that value returned by object is not null. it will be pass if returned.

#### XML runner
- XML runner allows user s to call  locators and different test class
- using the XML runner, the automated test cases are executed
- the report gets generated basesd on the results of the XML runner.
- 
#### Runner.xml
`<?xml version="1.0" encoding="UTF-8"?>`
`<!DOCTYPE suite SYSTEM "http://testng.org/testng-1.0.dtd">`
`<suite name="SmokeSuite">`
    `<test name="LoginclassTestCase">`
        `<classes>`
            `<class name="MyTestProject.Test.LoginTest"/>`
         `</classes>`
    `</test>`
`</suite>`
##### Steps to run runner.xml
1. Go to Edit Configuration
2. Click on the add (+) to add new configuration
3. Click on testNG
4. Give name "Runner"
5. select the "Suite" from the Test Kind dropdown.
6. Select the file in the suite input field.
7. Then click on apply and ok.

#### TestNG Reporting
- Once we execute test cases using TestNG, it will generate a default HTML report
- Execute the testing.xml file and refresh the project.
- Navigate to 'test-output' folder. Now you should find a report "examlable-report.html". this is the default report generated by TestNg.

##### Steps
1. open the edit configuration of Runner that you have created.
2. go to listeners
3. click on the use reporters
3. click apply and ok.


#### Common Questions
Why do we need RemoteWebDriver class?
What does Browser Drivers do?
When a test script is executed with the help of WebDriver, the following tasks are performed in the background: Why do we use Chromium Driver Class?
What are important methods defined in WebDriver?

--- 


# OOP Concepts

Basic concepts
- oop ?
- class
- object
- encapsulation
- inheritance and its types
- polymorphism
- overloading
- overriding
- abstrction
- class or interface
- constuctors and its types
- access modifier, setter and getter
- final,finally, static, this keyword


### Object-Oriented Programming (OOP)
- OOP is a programming paradigm that structures code around the concept of "objects," which can encapsulate(contian) data ( variable) and behavior ( methods). In OOP, programs are designed by modeling real-world entities as object and defining their interactions.
- This paradigm is based on four key principles:
    1. Encapsulation
    2. Inheritance
    3. Polymorphism
    4. Abstraction

### Encapsulation:
-  Bundling of data (attributes) and the methods (functions) that operate on the  data into a single unit, called a class. This restricts access to some of the object's components  and prevents the accidental modification of data.
 example 
- Class: BankAccount. 
- Data (Encapsulated): Account balance, account holder name
- Methods: Deposit, withdraw.
- Encapsulation ensures that the account balance can only be modified through defined methods, preventing unauthorized access


### Inheritance: 
- A mechanism that allows a class to inherit properties and behaviors from another  class. It promotes code reuse and establishes a hierarchy of classes.

example
- Base Class: Person
-  Properties: Name, Age, Address, Phone 
- Behaviors: UpdateAddress(new_address), Contact()
- Derived Class: Student 
- Inherits from Person and adds properties like marks, subject, GetGrade(), Enrol(subjects), Study() production. 
- Inheritance models the relationship between general entities (Person) and more specific entities (Student).

### Polymorphism:
- It means Many form. a property having many form. in simple words we can define polymorphism as the ability of a same message to be displayed in more than one form. 
- when the same entity(functionl or object) behave differently in diffently scenarios it is knwo as polymorphism.
--- Two types of polymorphism ---

*compile time* (function overloading, operator overloading).
- Function Overloading occurs when a two or more functions can have same name but different parameters.
*run time* (function overriding  )

- Function Overriding occurs when a drive class has a definition of one or more member of a base class.

### Abstraction 
- Data hiding is the process of protection members of a class from uninteded changes whereas, abstraction is hiding the implementation details and showing only important/ useful parts to the user.
- In simple terms, it is hiding the unnecessary details & showing only the essential parts/functionalities to the user.
- Data binding : Data binding is a process of binding the application UI and businesslogic. Any change made in the business logic will reflect directly to the application UI.


Abstraction is achieved in 2 ways :
- Abstract class
- Interfaces (Pure Abstraction)

1. Abstract Class
- An abstract class must be declared with an abstract keyword.
- It can have abstract and non-abstract methods.
- It cannot be instantiated.
- It can have constructors and static methods also.
- It can have final methods which will force the subclass not to change the body the method.

Constructor chaining, when we create the object of child class, first of all it call the constuctor of parent class then call the constructor of child class.

2. Interfaces ( pure abstraction)
- All the fields in interfaces are public, static and final by default
- All methods are public & abstract by default.
- A class that implements an interface must implement all the methods declared in the interface.
- Interfaces support the functionality of multiple inheritance.

example (Abstraction in a Remote Control) 
- Abstraction: RemoteControl 
- Methods: PowerOn, PowerOff, ChangeChannel
- Abstraction simplifies the interaction with a complex TV system, allowing users to control it without understanding its internal workings.


### class
- blue print, Class is a user-defined data type which defines its properties and functions. Class is the only logical representation of the data. For example, Human being is a class. The body parts of a human being are its properties, and the actions performed by the body parts are known as functions. The class does not occupy any memory space till the time an object is instantiated.

### object:
- entity of a class, property ( member variables), actions ( member functions). when a class is defined no memory is allocated but when it is instantiated ( i.e., object is created) of that class.
- Object is a run-time entity. It is an instance of the class. An object can represent a person, place or any other item. An object can operate on both data members and member functions.
- example human is a class. body parts is a member variables, action we performed is called the member functions.
- Note : When an object is created using a new keyword, then space is allocated for the variable in a heap, and the starting address is stored in the stack memory.
- ‘this’ keyword : ‘this’ keyword in Java that refers to the current instance of the class. In OOPS it is used to:
1. pass the current object as a parameter to another method
2. refer to the current class instance variable

i.e., pms.
 ```
class Passowrd{
 
     //data member
     String email;
     String password;

     //member function (methods)

//this: this is the keyword in the java,that tells which object calls this function. 
    public void showPassword(){
    System.out.println(this.email);
    System.out.println(this.password);
    }
}

public class Main(){
    public static void main(String args[]){
    
    //object of Passowrd class
  
     Passowrd obj1 = new Password();
    
     obj1.email = "test@gmail.com";
     obj1.password = "Tester@54321";

     //print infor
     obj1.showPassword();
}
```
example pen or oop class
```
package OOPs;
import java.util.Scanner;

//pen clas
class Pen{
    String color;
    String type;
    int price;

    public void write(){
        System.out.println("write some thing");
    }

    public void showInfo(){
        System.out.println(this.color);
        System.out.println(this.price);
        System.out.println(this.type);
    }
}
public class OOPs {

    public static void main(String args[]){

         Scanner scanner = new Scanner(System.in);


         Pen p1 = new Pen();
         p1.color = scanner.nextLine();
         p1.price = scanner.nextInt();
         p1.type = scanner.nextLine();


         //show details
        p1.showInfo();

    }
}
```

### Constructor 

- it is the special type of function that is automatically called when object is ceated. having same name as the class name.
- constructor does not return anything. ( dont have any return type)
- call only one time for one object. ( calls when object is created)


#### Example of constructor 
Student s1 = new Student();

- Student: data type of s1 object
- new: it is keyword in java that allocate a new space in memory with the name of Student. 
- Student(): non parameterized constructor. 

there are 3 types of constructor in java
1. non parameterized constructor
- A constructor which has no argument is known as non-parameterized constructor(or no-argumentconstructor). It is invoked at the time of creating an object. If we don’t create one then it is created by default by Java.

example
```
package OOPs;
import java.util.Scanner;
class Student {
    // non parameterized constructor
   
    String name;
    int marks;
    public void showInfo(){
        System.out.println(this.name);
        System.out.println(this.marks);
    }
     Student(){
        System.out.println("Object is Created");
    }
}
public class OOPs {
    public static void main(String args[]){
          Student s1 = new Student();
    }
}
```
2. Parameterized Constructor.
- A parameterized constructor is a type of constructor that accepts parameters when an object is created
example
```
package OOPs; 

import java.util.Scanner;

class Student {
    String name;
    int marks;
    Student(String name, int marks){
       this.name = name;
        this.marks = mar
    }
    
    public void showInfo(){
        System.out.println(this.name);
        System.out.println(this.marks);
    }
}

public class OOPs {
    public static void main(String args[]){
         Scanner scanner = new Scanner(System.in);
         String name = scanner.nextLine();
         int marks = scanner.nextInt();
         
          Student s1 = new Student(name,marks);
          s1.showInfor();
    }
}
```

3. copy constructor:  
- copy and object and put into and other object
example
```
package OOPs;

import java.util.Scanner;

class Student {
    String name;
    int marks;

    Student(Student s2){
        this.name = s2.name;
        this.marks = s2.marks;
    }
    
    Student(){

    }
    
    public void showInfo(){
        System.out.println(this.name);
        System.out.println(this.marks);
    }
}

public class OOPs {

    public static void main(String args[]){
          Scanner scanner = new Scanner(System.in);
          Student s1 = new Student();
          s1.name = scanner.nextLine();
          s1.marks = scanner.nextInt();
          
        Student s2 = new Student(s1);
        s2.showInfo();
    }
}
```
4. destructor
- Because Java is a garbage collected language you cannot predict when (or even if) an object will be destroyed. Hence there is no direct equivalent of a destructor.
  
### Polymorphism ( many forms)

1. function overloading - compile time
2. function overriding  - runtime


***Function overLoading  ( same name but different parameters)***

- make diff return type of paramerter if parameter are same in quantity
- make diff number of parameter in quantity if return type are same
example with code. 

Example of polymorphism
```
package OOPs;
class Student {
    String name;
    int marks;
    
    public void showInfo(String name, int marks){
        System.out.println(name);
        System.out.println(marks);
    }
    
    public void showInfo(String name){
        System.out.println(name);
    }
}

public class OOPs {

    public static void main(String args[]){
         Student s1 = new Student();
         s1.name = "test";
         s1.marks = 10;
         s1.showInfo(s1.name);
         s1.showInfo(s1.name, s1.marks);
    }
}
```
***Runtime Polymorphism : Runtime polymorphism is also known as dynamic polymorphism.***
- Function overriding is an example of runtime polymorphism. Function overriding means when the child class contains the method which is already present in the parent class. Hence, the child class overrides the method of the parent class. 
- In case of functionoverriding, parent and child classes both contain the same function with a different defination. the call to the function is determined at runtime is  known as run time polymorphism.

### Inheritance
- one class wants to use the property of other class

example
```
package OOPs;
class Person{
    String name;
    int age;
    int phone;
}
class Student extends Person{
    int marks;
    public void showDetails(){
        System.out.println(this.name+" "+ this.age+ " "+ this.marks);
    }
}
class Teacher extends  Person{
    int salary;
    public void showDetails(){
        System.out.println(this.name+" "+ this.age+ " "+ this.salary);
    }
}
public class OOPs {
    public static void main(String args[]){
         Student s1 = new Student();
         s1.marks = 12;
         s1.age = 20;
         s1.name = "student";
         s1.showDetails();

         Teacher t1 = new Teacher();
         t1.name = "Teacher";
         t1.age = 30;
         t1.salary = 1000;
         t1.showDetails();
    }
}
```
1. Single Level inheritance (we have one base class and one drive class)

example
```
class Shap{
    public void printArea(){
    
        System.out.println("Display Area");
    }
}

class Triangle extends Shap{

    public void printArea(int l, int h){
        System.out.println(1/2*l*h);
    }
}
```

2. Multi Level inheritance ( chaining of classes )

example
```
class Shap{

    public void printArea(){
    
        System.out.println("Display Area");
    }
}

class Triangle extends Shap{

    public void printArea(int l, int h){
        System.out.println(1/2*l*h);
    }
}
class EquilateralTriangle extends Triangle{

    public void printArea(int l, int h){
        System.out.println(1/2*l*h);
    }
}
```
3. Hierarchial Inheritance ( one base class and multiple child class inherit that base class )
example
```
class Person{

    String name;
    int age;
    int phone;
}

class Student extends Person{
    int marks;
   
    public void showDetails(){
        System.out.println(this.name+" "+ this.age+ " "+ this.marks);
    }
}

class Teacher extends  Person{
    int salary;
    public void showDetails(){
        System.out.println(this.name+" "+ this.age+ " "+ this.salary);
    }
}

```

5. Hybrid Inheritance ( combination  of one or more type) hierarchial plus multi-level.


### Access Modifiers 

1. Private: The access level of a private modifier is only within the class. It can not be accessed from outside the class.

2. Default: The access level of a default modifier is only within the package.  cannot be accessed from outside the package. If you do not specify any access level, it will be the default.

3. Protected: The access level of a protected modifier is within the package a outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package.

4. Public: The access level of a public modifier is everywhere. It can be access from within the class, outside the class, within the package and outside the package.



### Getters & Setter
- get the value from the private variable
- set the value to private variable

Example of Setter and Getter.
```
package OOPs;
class Account{

    private int balance;
    
    public int getBalance(){
        return this.balance;
    }
    
    public void setBalance(int balance){
        this.balance = balance;
    }
}

public class OOPs {
    public static void main(String args[]){
    
        Account obj = new Account();
        obj.setBalance(100);
        System.out.println(obj.getBalance());
    }
}
```

### Abstraction 
- Data hiding is the process of protection members of a class from uninteded changes whereas, abstraction is hiding the implementation details and showing only important/ useful parts to the user.
- In simple terms, it is hiding the unnecessary details & showing only the essential parts/functionalities to the user.
- Data binding : Data binding is a process of binding the application UI and businesslogic. Any change made in the business logic will reflect directly to the application UI.


Abstraction is achieved in 2 ways :
- Abstract class
- Interfaces (Pure Abstraction)

1. Abstract Class
- An abstract class must be declared with an abstract keyword.
- It can have abstract and non-abstract methods.
- It cannot be instantiated.
- It can have constructors and static methods also.
- It can have final methods which will force the subclass not to change the body the method.

Constructor chaining, when we create the object of child class, first of all it call the constuctor of parent class then call the constructor of child class.

2. Interfaces ( pure abstraction)
- All the fields in interfaces are public, static and final by default
- All methods are public & abstract by default.
- A class that implements an interface must implement all the methods declared in the interface.
- Interfaces support the functionality of multiple inheritance.

example (Abstraction in a Remote Control) 
- Abstraction: RemoteControl 
- Methods: PowerOn, PowerOff, ChangeChannel
- Abstraction simplifies the interaction with a complex TV system, allowing users to control it without understanding its internal workings.

 Example of Abstract class
 ```
package OOPs;

abstract class  Animal{
    abstract public void walks();
}

class Hours extends Animal {
    public void walks() {
        System.out.println("Walks on 4 legs");
    }
}

public class OOPs {

    public static void main(String args[]){
      Hours hours = new Hours();
      hours.walks();
    }
}
```

2. Interfaces ( pure abstraction)
- All the fields in interfaces are public, static and final by default
- All methods are public & abstract by default.
- A class that implements an interface must implement all the methods declared in the interface.
- Interfaces support the functionality of multiple inheritance.

 Example of Interfaces
 ```
package OOPs;

interface Animal{

   String color = "Black";
    void walks();
}

interface Red { 
}

class Hours implements  Animal , Red{
    public void walks() {
        System.out.println("Walks on 4 legs");
    }
}

public class OOPs {

    public static void main(String args[]){
      Hours hours = new Hours();
      hours.walks();
    }
}
```




