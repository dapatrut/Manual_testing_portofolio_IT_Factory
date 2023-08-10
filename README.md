# Final project for ITF Manual Testing Course

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application.

Application under test: [Orange_HRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login).

Original documentation: [Orange_HRM](https://www.orangehrm.com/assets/Files/Complete-Administrative-User-Guide.pdf?url=/Files/Complete-Administrative-User-Guide.pdf).

Tools used: JIRA and Zephyr Squad.

# Functional specifications

The application chosen by me for testing is [Orange_HRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login), the "Admin" module: "User Management" and "Job" sections.

The test project was created using the Jira tool. It contains two epics, one for the "User Management" section, with the requirement to verify the functionality to administer users as an Admin, and the second one for the "Job" section, in which all the information related to the "Job" field can be accessed and assigned to users.

# 1 Testing section

## 1.1 Test Planning

The Test Plan is designed to describe all details of testing for the "Admin" module, "User Management" and "Job" sections from the OrangeHRM application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan.

### 1.1.1 Roles assigned to the project and persons allocated
  - Project manager - Dan Calinici
  - Product owner - Mihai Ionescu
  - Software developer - Ionut Moldovan
  - QA Engineer - Daniela Patrut

### 1.1.2 Entry criteria defined:
  - Functional specifications are defined
  - Roles needed for the project are allocated
  - Initial project risks were detected and mitigated

### 1.1.3 Exit criteria defined
  - Number of unresolved bugs is insignificant or they have low priority
  - All tests have been executed
  - All resolved bugs have been re-tested and approved by the QA team
  - Deadline was reached
  - No detected major risk remained un-mitigated.

### 1.1.4 Test scope
   - Tests in scope: All the features of the "User Management" and "Job" sections which were defined in software requirement specifications need to be tested using functional testing (Black-box testing) and GUI testing.
  - Tests not in scope: performance testing, integrations of the "Admin" module with other modules, compatibility testing with multiple browsers.

### 1.1.5 Risks detected
  - Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial.
  - Product risks: validation constraints on the fields might be too restrictive to the end-user.

### 1.1.6 Evaluating entry criteria
The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

### 1.1.7 Bug Report
Bug reports are created in order to provide the development team and the project managers with exhaustive information about the discovered defects. They are helpful in determining causes of the errors and correcting them.

## 1.2 Test Monitoring and Control
It will be done by generating periodic reports that reflect the current status of the test.

## 1.3 Test Analysis
The testing process will be executed based on the above requirements for the "User Management" and "Job" sections. The following test conditions were found:

  - Enter data for all available fields and verify that the admin user is added;
  - Leave mandatory fields empty and check that the "Shift Name" on "Work Shifts" subsection cannot be added;
  - Adding an attachment;
  - Checking text fields with both valid and invalid values (positive and negative testing);
  - Checking check boxes functionality;
  - Checking the correct operation of "Reset" button;
  - Check the maxim characters for text fields in "Job" section.

## 1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are: boundary value analysis, equivalence partitioning and use case testing.

Test cases:


The test cases with steps can be viewed here:


## 1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

  - Testing environment is up and running: [Orange_HRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login)
  - Access to the testing environment is given: Username: Admin | Password: admin123
  - Cycle summary was created
  - Test cases were added to the cycle summary.

## 1.6 Test Execution

  - Test cases are executed on the created test Cycle Summary:
    
  - Bugs have been created based on the failed tests. The complete bug reports can be found here:
    
List of Bugs:

  - Full regression testing is needed after the bugs are fixed.

## 1.7 Test Completion
  - Exit criteria were evaluated and passed
  - The traceability matrix was generated and can be found here: 
  - Test execution chart was generated, the final report shows that a number 6 tests have failed of a total of 24
  - A number of 24 test cases were planned for execution and all of them were executed
  - A number of 6 total bugs were found, from which the priority is: 2 are high, 2 are medium and 2 are low.











&nbsp;
### Introduction
---
*Playground* is a ***suite*** of **Selenium and RoboBrowser** automated tests for [Orange_HRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login).

*Playground* is a ***suite*** of **Selenium and RoboBrowser** automated tests for [Orange_HRM](https://opensource-demo.orangehrmlive.com/web/index.php/auth/login "The best search engine for privacy").

> Dorothy followed her through many of the beautiful rooms in her castle.
>
> The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.
> > The Witch bade her clean the pots and kettles and sweep the floor and keep the fire fed with wood.   

1. First item
2. Second item
3. Third item
5. Fourth item

1. First item
2. Second item
3. Third item
    1. Indented item
    2. Indented item
4. Fourth item

- First item
- Second item
    - hello
- Third item
    - Indented item
    - Indented item
- Fourth item
  - sal


```
<html>
   <head>
     <title>Test</title>
   </head>
   ```
  
1. Open the file containing the Linux mascot.
2. Marvel at its beauty.

    ![3.PNG](/assets/images/tux.png)
   
3. Close the file.

| Syntax | Description |
| --- | ----------------- |
| Header | Title |



| Paragraph | Text |

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |



- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media



![Tux, the Linux mascot](/1.GIF)

<img src="/1.GIF" width="150" height="50">


| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header  shdxjhzhhzd    | Title   zjhgjtryj    | Here's this rzjjjtgfdgdfhtgjhfxgusdhfxhgshgdhdgcufhdjzggdfgSFVhcvhvchjdhjvbdhjvbhjbdvhjfdbjhfdf jhdbfhsB fdshjGB   |
| Paragraph zjzd  | Text  dhxtjryjh      | And more      |


