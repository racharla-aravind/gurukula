## How to clone the repository

git clone https://github.com/racharla-aravind/gurukula.git

## Prerequisites to run the tests
 # Java 1.8
 # Maven 3.3.9

## How to run the test(s)

 # To run all the test use the below command from the project folder path
 - mvn clean install -DbrowserName=chrome (If running for the first time, to install all the dependencies and run the tests)
 - mvn tests -DbrowserName=chrome (if dependencies are already available)
 NOTE: If no browserName is specified, default value will be chrome
 
 # To run single module (Eg: All LoginTests) use the below command from the project folder path
 - mvn test -Dtest=com.gurukulam.tests.LoginTests.java 
 
 # To run a single test (Eg: testSuccessfulLogin() of LoginTests) use the below command from the project folder path
 - mvn test -Dtest=com.gurukulam.tests.LoginTests.java#testSuccessfulLogin

## How to look for the logs
 - Log file is available in the project folder path with the same "gurukulam.log"

## Screenshots path
 - For each test at the end of the validation or on test failure a screenshot is saved with the file name pattern "<ModuleName>_<TestCaesName>" under "<project_folder>/reports/screenshots" folder.

## TO-DO List:
 - HTML reporting or any other better reporting 
 - Logs Summary with just Test Case Name and Status for the test case
 - Remove implicit wait method 
 - Database Testing
 - Performance Testing

## Modules Covered:
 # Home Page
 # Login Page
 # Reset Your Password
 # Create A New Branch
 # Search For A Branch Using BranchName and BranchCode
 # Delete A Branch
 # View A Branch 
 # Edit A Branch
 # Search For A Staff Using StaffName and StaffBranch
 # Delete A Staff
 # View A Staff 
 # Edit A Staff
 # Registration
 # Account Settings

## Observations:
 # Placed a separate document in the project folder for bugs (Bugs.docx)
 # Placed a separate document in the project folder for Observations (NOTES.docx)

## Test Cases Document: 
 # Placed a separate document in the project folder (TestCases.xlsx)
