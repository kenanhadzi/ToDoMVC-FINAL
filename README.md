Test Suite
Our test suite includes unit tests, integration tests, and end-to-end tests, all of which are written in Jest and run as part of our Continuous Integration (CI) pipeline.


Test Scenarios
Our tests cover a variety of scenarios, including: Adding tasks (cypress\e2e\Adding-tasks.cy.js), Editing tasks(cypress\e2e\Editing-tasks.cy.js), Completing tasks(cypress\e2e\Completing-tasks.cy.js), Filtering tasks(cypress\e2e\Filtering-tasks.cy.js), Deleting tasks(cypress\e2e\Deleting-tasks.cy.js) and Task counter(cypress\e2e\Task-counter.cy.js).



CI Pipeline

Our CI pipeline runs our test suite automatically whenever code is pushed to our main branch.Here is GitLab repository link (https://gitlab.com/kenan.hadzimahmutovic/todomvc-finish.git). The pipeline consists of the following steps:

Checkout code from the repository
Install dependencies
Build the application
Run the test suite
If any of the steps fail, the pipeline will fail and send a notification to the development team.




Test Execution Reports

Our test suite generates reports in the form of HTML and JSON files that can be accessed from the CI system.You can find them in cypress\reports folder. The reports include detailed information about each test, including its status (pass or fail), the input values used, and any error messages generated during the test.To interpret the test execution reports, simply open the HTML file in a web browser and navigate to the test results page.To interpret the test execution reports in JSON format simply open the JSOn file and there you can see all reports from the tests. The page includes a summary of the tests that were run and their status, as well as detailed information about each test.




Deliverables:


Here is a link of GitHub repository (https://github.com/kenanhadzi/ToDoMVC-FINAL.git).
For execution open new terminal in Visual Studio Code and type samo of these commands: 
 (type npm run triggerAllTests-headlesschrome)
     (type npm run triggerAllTests-headlessfirefox)
     (type npm run triggerAllTests-headlessinedge)
    (type npm run triggerAllTests-headlessinchrome)
     (type npm run triggerAllTests-headedinfirefox )
    (type npm run triggerAllTests-headedinedge )
   
    
    
 Findings:

The ToDoMVC application has a relatively simple design and structure, which makes it easy to understand and modify.
During testing, no problem was observed and all tests are passed. Reports are saved in (cypress\reports) folder where you can see all details.
The test suite provided good coverage of the identified functionality and features and helped identify many of the issues.


