Test Cases:

Test case ID:TC-01

Test Scenario: Verify login with correct credentials

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       
Expected: Login allowed

Actual: Login allowed

Result: Pass

___________________________________________________________________________________


Test case ID: TC-02

Test Scenario: Verify login with no credentials

Steps:

       -Open the website in a browser
       -Press the login button
       
Expected: Login blocked

Actual: Login allowed 

Result: Failed

___________________________________________________________________________________


Test case ID: TC-03

Test Scenario: Verify login with age above 100

Steps: 
       
       -Open the website in a browser
       -Fill the name and age > 100
       -Press the login button
       
Expected: Login blocked

Actual: Login allowed 

Result: Failed

___________________________________________________________________________________


Test case ID: TC-04

Test Scenario: Verify login with age below 13

Steps: 

       -Open the website in a browser
       -Fill the name and age < 13
       -Press the login button
       
Expected: Login blocked

Actual: Login allowed 

Result: Failed

___________________________________________________________________________________


Test case ID: TC-05

Test Scenario: Verify correct answer in Q1

Steps:
       
       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer
       
Expected: Navigate to Q2

Actual: Navigates to Q2

Result: Pass

___________________________________________________________________________________


Test case ID: TC-06

Test Scenario: Verify wrong answer in Q1

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the wrong answer
       
Expected: Wrong answer page

Actual: Navigates to Q2 

Result: Failed

___________________________________________________________________________________



Test case ID: TC-07

Test Scenario: Verify Quit Game button

Steps:

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the quit game button
       
Expected: Exit quiz

Actual: Error page 

Result: Failed

___________________________________________________________________________________


Test case ID: TC-08

Test Scenario: Verify correct answer in Q2

Steps:

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the correct answer in Q2
       
Expected: Navigate to Q2

Actual: Navigates to Q2

Result: Pass

___________________________________________________________________________________



Test case ID: TC-09

Test Scenario: Verify wrong answer in Q2

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the wrong answer in Q2
       
Expected: wrong answer page

Actual: No response 

Result: Failed

___________________________________________________________________________________


Test case ID: TC-10

Test Scenario: Verify correct answer in Q3

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the correct answer in Q2
       -click on the correct answer in Q3
       
Expected: Shows quiz completed successfully pop up

Actual: Shows quiz completed successfully pop up

Result: Pass

___________________________________________________________________________________



Test case ID: TC-11

Test Scenario: Verify wrong answer in Q3

Steps: 
       
       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the correct answer in Q2
       -Click on the wrong answer in Q3
       
Expected: Wrong answer page

Actual: Redirected to wrong answer page 

Result: Pass

___________________________________________________________________________________


Test case ID: TC-12

Test Scenario: Verify retry button in wrong page

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the correct answer in Q2
       -Click on the wrong answer in Q3
       
Expected: Navigates back to the Q1

Actual: Retry button not given

Result: Failed

