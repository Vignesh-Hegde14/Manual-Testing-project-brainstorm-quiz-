# Bug Reports

1.Bug ID: BUG_01

Title: Login allows users below 13 years

Environment: Chrome Browser, Windows 11

Severity: High :: 
Priority: High

Steps: 

      -Open the website in a browser
      -Fill the name and age <= 13
      -Press the login button
       
Expected: Error message


Actual: Redirects to Q1 page

___________________________________________________________________________________



2.Bug ID: BUG_02

Title: Login allows users above 1oo years

Environment: Chrome Browser, Windows 11

Severity: Medium :: 
Priority: Low

Steps:
      
       -Open the website in a browser
       -Fill the name and age > 100
       -Press the login button
       
Expected: Error message


Actual: Redirected to Q1 page

___________________________________________________________________________________


3.Bug ID: BUG_03

Title: Login allows users with no credentials

Environment: Chrome Browser, Windows 11

Severity: High :: 
Priority: High

Steps:
       -Open the website in a browser
       -Press login button with no credentials filled
       
Expected: Error message


Actual: Redirected to Q1 page

___________________________________________________________________________________



4.Bug ID: BUG_04

Title: Wrong answer in Question 1 proceeds to next question

Environment: Chrome Browser, Windows 11

Severity: High :: 
Priority: Medium

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the wrong answer in Q1
       
Expected: Wrong answer page 


Actual: Redirected to Q2 page

___________________________________________________________________________________


5.Bug ID: BUG_05

Title: Quit Game button redirects to invalid page

Environment: Chrome Browser, Windows 11

Severity: High :: 
Priority: Medium

Steps: 

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the quit game button
       
Expected: quits the game


Actual: Redirects to invalid page

___________________________________________________________________________________


6.Bug ID: BUG_06

Title: Wrong answer in Question 2 has no action

Environment: Chrome Browser, Windows 11

Severity: High :: 
Priority: Medium

Steps:

       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the wrong answer in Q2
       
Expected: Wrong answer page


Actual: No response

___________________________________________________________________________________


7.Bug ID: BUG_07

Title: Wrong answer page has no navigation options

Environment: Chrome Browser, Windows 11

Severity: Low :: 
Priority: Low

Steps: 
      
       -Open the website in a browser
       -Fill the name and age with correct credentials
       -Press the login button
       -Click on the correct answer in Q1
       -Click on the correct answer in Q2
       -Click on the wrong answer in Q3
       
Expected: Wrong answer page has retry button


Actual: No retry button 
