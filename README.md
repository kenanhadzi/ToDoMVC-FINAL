Test Suite
Our test suite includes unit tests, integration tests, and end-to-end tests, all of which are written in Jest and run as part of our Continuous Integration (CI) pipeline.


Test Scenarios
Our tests cover a variety of scenarios, including: Adding tasks, Editing tasks, Completing tasks, Filtering tasks, Deleting tasks and Task counter.



CI Pipeline

Our CI pipeline runs our test suite automatically whenever code is pushed to our main branch.Here is GitLab repository link (https://gitlab.com/kenan.hadzimahmutovic/todomvc-finish.git). The pipeline consists of the following steps:

Checkout code from the repository
Install dependencies
Build the application
Run the test suite
If any of the steps fail, the pipeline will fail and send a notification to the development team.




Test Execution Reports

Our test suite generates reports in the form of HTML and JSON files that can be accessed from the CI system.You can find them in cypress\reports folder. The reports include detailed information about each test, including its status (pass or fail), the input values used, and any error messages generated during the test.To interpret the test execution reports, simply open the HTML file in a web browser and navigate to the test results page.To interpret the test execution reports in JSON format simply open the JSOn file and there you can see all reports from the tests. The page includes a summary of the tests that were run and their status, as well as detailed information about each test.


