# qa-automation-login-playwright  

This project demonstrates a professional automated testing approach for login functionality using Playwright. The focus is on positive, negative, security, and edge-case scenarios from a QA perspective.  

## Test Scope  

  - Positive login
  - Negative cases (invalid username/password, empty username/password)
  - Security mindset (SQL Injection, Path Traversal)
  - UI validation

## Test Case  

  TC001 - Login success with valid credentials  
  TC002 - Login failed with invalid credentials  
  TC003 - Login failed with invalid username and valid password  
  TC004 - Login failed with valid username and invalid password    
  TC005 - Login failed when username is empty  
  TC006 - Login failed when password is empty  
  TC007 - Login failed when username and password is empty  
  TC008 - bypass with path traversal  
  TC009 - SQL Injection
