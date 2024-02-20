# Jira-and-Zephyr - Testing project for OrangeHRM
Functional specifications
The below Story was created in JIRA and describes the functional specifications of MyInfo module and Login functionallity.

1 Testing section
1.1 Test Planning
The Test Plan is designed to describe all details of testing for MyInfo module and Login functionallity from the OrangeHRM application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

1.1.1 Roles assigned to the project and persons allocated
Project manager - Ion Popa
Software developer - Lidia Popa
QA Engineer - Irina Runcanu
1.1.2 Entry criteria defined
functional specifications are defined
roles needed for the project are allocated
initial project risks were detected and mitigated
1.1.3 Exit criteria defined
number of unresolved bugs is insignificant or they have low priority
all tests have been executed
all resolved bugs have been re-tested and approved by the QA team
deadline was reached
no detected major risk remained un-mitigated
exploratory regression testing must be performed on the My Info module, which includes the Dependents section
1.1.4 Test scope
Tests in scope: All the feature of MyInfo module which were defined in software requirement specs need to be tested: functional testing, GUI testing and API testing
Tests not in scope: performance testing, integrations of MyInfo module with other modules, compatibility testing with multiple browsers
1.1.5 Risks detected
Project risks: lack of experience of the QA team, short deadline of Zephyr Squad trial, unavailability of test environment
Product risks: validation constraints on the fields might be too restrictive to the end-user
1.1.6 Evaluating entry criteria
The entry criterias defined in the Test Planning phase have been achieved and the test process can continue.

1.2 Test Monitoring and Control
Various periodic reports were generated to reflect the current status of the testing process, in case of major problems control measures could be taken. The following status report was generated after 40% of the test cases were executed:

1.3 Test Analysis
The testing process will be executed based on the above requirements for MyInfo module. The following test conditions were found:

Enter data only for mandatory fields and check that personal details of an employee are created/updated
Enter data for all available fields and check that personal details of an employee are created/updated
Leave mandatory fields empty and check that personal details of an employee cannot be created/updated
View dependant details and check they are correct
Test the Login functionallity
Check all validation constraints for the fields

1.4 Test Design
Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are boundary value analysis, equivalence partitioning and use case testing.

Test cases:

The test cases with steps can be viewed here: 

1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

Testing environment is up and running: https://opensource-demo.orangehrmlive.com/
Access to the testing environment is given: Username : Admin | Password : admin123
Cycle summary was created
Test cases were added to the cycle summary
Postman collection with the dependents API methods was created
Authorization token was created for accessing the API
1.6 Test Execution
Test cases are executed on the created test Cycle summary: Dependents_cycle_summary_execution.pdf
Bugs have been created based on the failed tests. The complete bug reports can be found here: Dependents_created_bugs.pdf
Date format is not dd/mm/yyyy
Future "Date of Birth" can be selected from calendar
Only 50 characters are allowed for "Please Specify" field
Only 50 characters are allowed for "Name" field
Relationship "parent" is missing
API tests are executed based on the checklist. The collection used can be found here: JSON file with the collection of requests created for the Dependents API
Full regression testing is needed after the bugs are fixed
1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: Traceability_matrix.csv
Test execution chart was generated, the final report shows that a number 5 tests have failed of a total of 23
A number of 23 test cases were planned for execution and all of them were executed
A number of 5 total bugs were found, from which the priority is: 1 is high, 4 are medium and 1 is low
