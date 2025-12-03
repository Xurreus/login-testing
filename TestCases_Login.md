# Test Cases – Login Page

| ID   | Test Case Description           | Steps                                                 | Expected Result |
|------|--------------------------------|-------------------------------------------------------|----------------|
| TC01 | Login with valid credentials    | Enter valid email and password, click Login          | User is redirected to dashboard |
| TC02 | Invalid password                | Enter valid email + wrong password, click Login      | Error: "Invalid credentials" |
| TC03 | Invalid email format            | Enter invalid email (e.g., abc@), click Login       | Error: "Enter a valid email" |
| TC04 | Empty fields                    | Click Login without entering email or password      | Error: "Email and Password are required" |
| TC05 | Password min length             | Enter password <6 characters                         | Error: "Password must be at least 6 characters" |
| TC06 | Case sensitivity check          | Enter email with different letter case               | Login should succeed/fail based on system rules |
| TC07 | Remember me functionality       | Tick Remember Me, login and close browser            | User remains logged in on next visit |
