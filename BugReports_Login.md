# Bug Report List – Login Page

## Bug 01
**Title:** Login button unresponsive  
**Steps:** Enter valid credentials, click Login  
**Expected:** Redirect to dashboard  
**Actual:** Nothing happens  

## Bug 02
**Title:** Invalid email accepted  
**Steps:** Enter 'abc@' as email, valid password, click Login  
**Expected:** Error: "Enter a valid email"  
**Actual:** Form allows login  

## Bug 03
**Title:** Password error message not clear  
**Steps:** Enter wrong password  
**Expected:** "Invalid credentials" message  
**Actual:** Generic error displayed  

## Bug 04
**Title:** Remember Me not working  
**Steps:** Tick Remember Me, login, close browser, reopen  
**Expected:** User stays logged in  
**Actual:** User needs to log in again
