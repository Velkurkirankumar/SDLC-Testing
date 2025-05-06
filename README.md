# SDLC

#### Difference between SDLC and STLC
- Software Development Life Cycle (SDLC) and Software Testing Life Cycle (STLC) are important parts of software engineering.
- SDLC has a broad scope; it consists of 6 phases:
```requirement analysis, design, development, testing, deployment, and maintenance.```
- On the other hand, STLC is a subset of SDLC. It has Focused scope, specially focus on the testing phase of SDLC.
- The Primary Goal of STLC is to ensure the quality, functionality and reliability of software through various testing activities.

#### What is Software Development Life Cycle ( SDLC) ?
- SDLC is a process followed for software building within a software organization.
- SDLC consists of a precise plan that describes how to develop, maintain, replace, and enhance specific software.
- The life cycle defines a method for improving the quality of software and the all-around development process.
- Software Development Life Cycle (SDLC) is a sequence of different activities performed during the software development process.

#### SDLC consist of 6 Phases:

- Requirement Analysis
- Software Design
- Software Build
- Testing
- Deployment
- Maintenance


#### What is Software Testing Life Cycle (STLC)?
- The Software Testing Life Cycle (STLC) is a systematic approach to testing a software application to ensure that it meets the requirements and is free of defects.
- It is a process that follows a series of steps or phases, and each phase has specific objectives and deliverables.
- The STLC is used to ensure that the software is of high quality, reliable, and meets the needs of the end-users.

##### STLC consist of 5 Phases

- Test Planning
- Test Case Development
- Test Environment Setup
- Test Execution
- Test Closure
- Capture100


#### Difference between SDLC and STLC


| **Aspect**       | **SDLC**                                                                 | **STLC**                                                                 |
|------------------|--------------------------------------------------------------------------|-------------------------------------------------------------------------|
| **Domain**       | SDLC is mainly related to software development.                          | STLC is mainly related to software testing.                             |
| **Focus**        | Besides development, other phases like testing are also included.        | It focuses only on testing the software.                                |
| **Phases**       | SDLC involves a total of six phases or steps.                            | STLC involves only five phases or steps.                                |
| **Team Size**    | More members (developers) are required for the whole process.            | Fewer members (testers) are needed.                                     |
| **Team Involved**| Development team makes plans and designs based on the requirements.      | Testing team (Test Lead or Test Architect) makes the test plans.        |
| **Objective**    | The goal of SDLC is the successful development of software.              | The goal of STLC is the successful testing of software.                 |
| **End Result**   | Helps in developing high-quality software.                               | Helps in making the software defect-free.                               |
| **Execution**    | SDLC phases are completed before the STLC phases.                        | STLC phases are performed after SDLC phases.                            |
| **Maintenance**  | Includes post-deployment support, enhancements, and updates.             | Regression tests are run; test cases and scripts are maintained.        |
| **Final Outcome**| Creation of reusable software systems.                                   | A thoroughly tested software system.                                    |



## Software Testing

- In software testing interviews, expect questions about the Software Testing Life Cycle (STLC), manual vs. automated testing, and common testing methodologies. You should also be prepared to discuss popular testing tools like Selenium, JMeter, and TestLink, understanding their applications and limitations. 

- Basic Testing Concepts:

- What is software testing?
Testing is the process of evaluating a software product's functionality and performance to ensure it meets requirements and is free from defects. 

- Why is testing important?
Testing ensures the quality of the software, reduces development costs by identifying issues early, and builds customer confidence. 

- Explain the Software Testing Life Cycle (STLC).
STLC defines the phases of testing, including planning, test design, environment setup, execution, defect tracking, and reporting. 

- What are the different types of software testing?
Common types include functional testing (unit, integration, system), non-functional testing (performance, security, usability), and regression testing. 

- What is the difference between verification and validation?
Verification ensures the product is built correctly (meeting the requirements), while validation ensures the right product is being built (meeting the customer's needs). 

- What is a defect?
A defect is a deviation from the expected behavior of the software, indicating a problem that needs to be fixed. 

- What is the difference between manual and automated testing?
Manual testing involves manually executing test cases, while automated testing uses software tools to execute tests. 

- What are the advantages and disadvantages of manual and automated testing?
Manual testing is good for exploratory and UI testing, while automated testing is good for repetitive, large-scale tasks and regression testing. 

- What is a test case?
A test case is a set of instructions that defines the steps to execute a test and the expected results. 

- What is a test scenario?
A test scenario is a broader context for a test case, describing the situation or context in which the test is performed. 

- What is regression testing?
Regression testing is the process of re-testing existing code after making changes to ensure that those changes haven't introduced new bugs. 

- What is smoke testing?
Smoke testing is a quick assessment of the core functionality of a software application to determine if it's in a stable state for further testing. 

- What is sanity testing?
Sanity testing is a more in-depth test of specific features or modules to verify that they are working as expected. 

##### Testing Tools:

- What are some popular testing tools? Examples include Selenium, JMeter, TestLink, Jenkins, and Cucumber. 
- What is Selenium? Selenium is a tool for automating web application testing, allowing for cross-browser testing and various scripting languages. 
- What is JMeter? JMeter is a performance testing tool used to simulate user load on web applications, APIs, and other systems. 
- What is TestLink? TestLink is a test management tool used to plan, execute, and track tests.
- What is Jenkins? Jenkins is a continuous integration and continuous delivery (CI/CD) tool that automates the build, testing, and deployment processes. 
- What is Cucumber? Cucumber is a behavior-driven development (BDD) framework that allows for the definition of test scenarios in a human-readable format. 
- What are the advantages and disadvantages of using automated testing tools? Automated tools can be more efficient and consistent, but require setup and maintenance. 
- How do you choose the right tool for a particular testing task? Consider the type of application, the complexity of the test, and the available resources. 
- What are some best practices for using testing tools? Design test cases that are clear, concise, and reusable. 


# Software Testing Questions and Answers

---

### 1. **What is Performance Testing?**

   **Answer:**
   **Performance Testing** is a type of non-functional testing used to determine how a system performs under a certain load. It evaluates the speed, scalability, and stability of an application under different conditions. Types of performance testing include:
   - **Load Testing**: Verifies that the system can handle the expected number of users.
   - **Stress Testing**: Tests the system beyond its normal load to identify breaking points.
   - **Spike Testing**: Tests the system's ability to handle sudden, extreme increases in load.
   - **Endurance Testing**: Verifies that the system can handle a constant load over an extended period.

---

### 2. **What is User Acceptance Testing (UAT)?**

   **Answer:**
   **User Acceptance Testing (UAT)** is the final phase of testing where the end-users test the software to ensure it meets their needs and requirements. UAT focuses on validating the functionality, usability, and compatibility of the software from the user's perspective. It helps confirm that the software is ready for release.

---

### 3. **What is a Defect Life Cycle?**

   **Answer:**
   The **Defect Life Cycle** refers to the series of stages a defect goes through from the moment it is identified until it is resolved. The typical stages in a defect life cycle include:
   1. **New**: The defect is identified.
   2. **Assigned**: The defect is assigned to a developer for fixing.
   3. **Open**: The defect is being worked on.
   4. **Fixed**: The defect has been fixed.
   5. **Retested**: The defect is retested to verify the fix.
   6. **Closed**: The defect is fixed and verified, and it is marked as closed.
   7. **Reopened**: If the defect persists after fixing, it is reopened for further attention.

---

### 4. **What is Exploratory Testing?**

   **Answer:**
   **Exploratory Testing** is an informal testing approach where testers actively explore the application without predefined test cases. The goal is to discover defects by interacting with the software and using their intuition, experience, and creativity to find unexpected behaviors. Testers might document their findings as they go.

---

### 5. **What is Test Environment Setup?**

   **Answer:**
   **Test Environment Setup** refers to preparing the environment where testing will take place. This includes installing the necessary software, configuring hardware, setting up databases, and ensuring the right tools and test data are available. It’s crucial to have the environment configured similarly to production to get realistic results during testing.

---

### 6. **What is a Smoke Test in the context of Continuous Integration?**

   **Answer:**
   In **Continuous Integration (CI)**, a **Smoke Test** is a set of basic tests that run automatically after every code commit to ensure that the build is stable enough for further, more in-depth testing. Smoke testing helps in detecting simple, critical defects that may break the application early in the testing cycle.

---

### 7. **What are the major differences between Black Box Testing and White Box Testing?**

   **Answer:**
   - **Black Box Testing**: Involves testing the software based on its inputs and outputs without knowledge of its internal workings. It focuses on functionality, usability, and overall behavior.
   - **White Box Testing**: Also known as **Structural Testing**, it involves testing the internal logic, code structure, and execution paths. Testers need to have knowledge of the source code and can test individual functions, branches, and loops.

---

### 8. **What is the purpose of a Test Case Traceability Matrix?**

   **Answer:**
   A **Test Case Traceability Matrix (TCTM)** is a tool used to ensure that every requirement is covered by a test case. It helps track the relationship between requirements and their corresponding test cases. By using a TCTM, you can ensure that all requirements are tested and that no requirement is overlooked.

---

### 9. **What is the role of a Test Architect?**

   **Answer:**
   A **Test Architect** is responsible for designing the overall test automation framework, defining the test strategy, and overseeing the implementation of testing procedures across multiple projects. They ensure that best practices are followed, tools are selected, and testing efforts are optimized for scalability and maintainability.

---

### 10. **What is the difference between a Bug and a Defect?**

   **Answer:**
   - **Bug**: A **bug** is a mistake or flaw in the software that causes it to behave unexpectedly. It is typically reported by testers during the testing phase.
   - **Defect**: A **defect** refers to any deviation from the expected behavior of the software. While "bug" is often used interchangeably with "defect," the term "defect" is often broader and may include issues introduced by developers, incorrect requirements, or even process problems.

---

### 11. **What is Risk-Based Testing?**

   **Answer:**
   **Risk-Based Testing** is a testing approach where tests are prioritized based on the risk of failure and its impact on the project or business. It focuses on identifying the areas of the application with the highest risk and allocating resources accordingly to mitigate those risks.

---

### 12. **What is Test-Driven Development (TDD)?**

   **Answer:**
   **Test-Driven Development (TDD)** is a software development process in which developers write tests before writing the actual code. The process follows three steps:
   1. Write a **test** for a new feature.
   2. Write just enough code to **pass** the test.
   3. **Refactor** the code to improve it while keeping the test passing.
   TDD encourages writing maintainable code with fewer defects by focusing on testing early.

---

### 13. **What is Continuous Integration (CI)?**

   **Answer:**
   **Continuous Integration (CI)** is the practice of integrating code changes into a shared repository several times a day. Automated tests run every time a change is committed to ensure that the code base remains stable. CI tools like Jenkins, GitLab CI, and Travis CI can help automate this process.

---

### 14. **What is API Testing?**

   **Answer:**
   **API Testing** is the process of testing the APIs (Application Programming Interfaces) directly, without a user interface, to ensure that they perform as expected. It involves checking the functionality, performance, reliability, and security of the APIs. Tools like Postman and SoapUI are commonly used for API testing.

---

### 15. **What is the difference between Functional and Non-Functional Testing?**

   **Answer:**
   - **Functional Testing**: Focuses on testing the software against the functional requirements, such as whether it performs the expected tasks (e.g., login, data entry, report generation).
   - **Non-Functional Testing**: Focuses on testing non-functional aspects of the software, such as performance, usability, security, and reliability. Examples include load testing, security testing, and user experience testing.

---

### 16. **What is Static Testing?**

   **Answer:**
   **Static Testing** is the process of reviewing the software's artifacts (such as code, design, and documentation) without executing the code. Techniques like code reviews, walkthroughs, and inspections are used to find defects early in the development process.

---

### 17. **What is the role of the QA (Quality Assurance) team in software testing?**

   **Answer:**
   The **QA team** is responsible for ensuring the overall quality of the software throughout its development lifecycle. Their role includes:
   - Developing testing strategies.
   - Creating and executing test plans and test cases.
   - Identifying and reporting defects.
   - Ensuring that the software meets the business requirements.
   - Conducting reviews and audits to ensure compliance with standards.

---

### 18. **What is a Test Harness?**

   **Answer:**
   A **Test Harness** is a collection of software and test data used to test the functionality of software components in isolation. It allows automated testing of software applications, ensuring that all aspects of the system are tested under controlled conditions.

---

### 19. **What is Regression Testing?**

   **Answer:**
   **Regression Testing** is the process of retesting an application after changes (like bug fixes, enhancements, or configuration changes) to ensure that previously functioning features have not been negatively affected by the changes.

---

### 20. **What is Black Box Testing?**

   **Answer:**
   **Black Box Testing** focuses on testing the software’s functionality from the user’s perspective without knowledge of its internal structure or code. Testers validate whether the system behaves as expected based on given inputs.

---

### 21. **What is White Box Testing?**

   **Answer:**
   **White Box Testing** involves testing the internal logic, code structure, and flow of the application. It requires knowledge of the software's source code and tests for conditions such as code coverage, paths, and loops.

---

### 22. **What is Usability Testing?**

   **Answer:**
   **Usability Testing** evaluates how user-friendly, efficient, and intuitive the software is for the end-users. Testers observe how users interact with the system and identify any difficulties they encounter.

---

### 23. **What is Boundary Value Analysis?**

   **Answer:**
   **Boundary Value Analysis** is a test design technique where test cases are designed to include boundary values (the edge of valid or invalid input ranges). It helps in identifying defects at the boundaries of input conditions.

---

### 24. **What is the Difference Between Alpha and Beta Testing?**

   **Answer:**
   - **Alpha Testing**: Performed by internal developers and testers to identify bugs before releasing the software to external users.
   - **Beta Testing**: Conducted by a select group of external users (or the public) to identify bugs and gather feedback before the final release.

---

### 25. **What is Load Testing?**

   **Answer:**
   **Load Testing** is the process of testing the system's ability to handle expected user loads. It ensures the software can handle the specified number of concurrent users and transactions without performance degradation.

---

### 26. **What is Stress Testing?**

   **Answer:**
   **Stress Testing** tests the system under extreme conditions or beyond the normal operating capacity to determine how it behaves under stress. The goal is to find the breaking point or failure threshold.

---

### 27. **What is a Test Plan?**

   **Answer:**
   A **Test Plan** is a detailed document that outlines the scope, objectives, resources, schedule, and methodology for testing an application. It provides guidelines for the testing process and ensures alignment with project requirements.

---

### 28. **What is an Automation Framework?**

   **Answer:**
   An **Automation Framework** is a set of guidelines or rules used for automating the testing process. It includes a combination of testing tools, libraries, and best practices that ensure the automation process is efficient, reusable, and scalable.

---

### 29. **What is a Test Suite?**

   **Answer:**
   A **Test Suite** is a collection of related test cases that are executed together. It helps in organizing tests based on functionality, modules, or any other criteria to ensure systematic testing.

---

### 30. **What is the Difference Between Smoke and Sanity Testing?**

   **Answer:**
   - **Smoke Testing**: A basic test to verify that the software build is stable and ready for more extensive testing.
   - **Sanity Testing**: Focuses on verifying specific functionalities after a bug fix or minor change to ensure they work as expected.

---

### 31. **What is the Role of Test Automation in Software Testing?**

   **Answer:**
   **Test Automation** helps in performing repetitive tests, speeding up the testing process, and improving accuracy. It is particularly useful for regression testing, performance testing, and repetitive testing tasks.

---

### 32. **What is Pair Testing?**

   **Answer:**
   **Pair Testing** is a collaborative testing technique where two testers work together on the same test case. One tester drives the testing while the other provides feedback, and both share their expertise to identify defects more effectively.

---

### 33. **What is Boundary Value Analysis?**

   **Answer:**
   **Boundary Value Analysis** focuses on testing at the boundaries of input values. This testing technique helps identify defects that occur at the edge of valid and invalid input ranges.

---
