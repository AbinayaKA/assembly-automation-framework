# assembly-automation-framework
This automation framework consists of test cases which covers the below scenarios in testing assembly website through Selenium (Java)
  1. Validating sending message funtionality from the intercom 
  2. Validating Book a demo functionality and capture success message 
  3. Verifying the number of lists available under the workflows category and returning the list

Pre-requisites:
  1. Install Java and IntelliJ
  2. Import maven dependencies in pom.xml file
  3. Import dependencies to class path 

Folders and Files:
  1. configuration: Includes the base configuration to set-up driver and initiate tests
  2. resources: Includes test data file to provide and update user input (Update driver location in REPLACE_ME)
  3. utils: Includes WebDriver functionalities and and config reader file to read input data
  4. pages and tests: Includes test cases and corresponding page objects

Test Execution:
AssemblyAutomationProject.xml must be executed which includes all the three classes.

