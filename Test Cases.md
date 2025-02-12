## 3. Test Cases for Financial Planner & Investment Advisor

| **Test Case ID** | **Test Scenario** | **Input** | **Expected Output** | **Status** |
|-----------------|-----------------|----------|------------------|----------|
| TC_001 | User Registration | Valid email, password, and user details | Account successfully created |
| TC_002 | User Registration | Invalid email format | Error message: "Invalid email format" |
| TC_003 | Login | Correct email and password | Redirect to dashboard |
| TC_004 | Login | Incorrect password | Error message: "Invalid credentials" |
| TC_005 | Budget Creation | Input budget amount | Budget successfully added |
| TC_006 | Expense Tracking | Input valid expense details | Expense recorded and categorized |
| TC_007 | Expense Tracking | Input empty amount field | Error: "Amount required" |
| TC_008 | Investment Tracking | Input stock ticker symbol | Portfolio updated with real-time data |
| TC_009 | Investment Tracking | Non-existent stock symbol | Error: "Invalid stock ticker" |
| TC_010 | Goal Setting | Input savings goal and target date | Goal successfully added |
| TC_011 | Goal Setting | Negative goal amount | Error: "Invalid amount" |
| TC_012 | Security - Password Reset | Request password reset with registered email | Password reset link sent |
| TC_013 | Security - Password Reset | Request with unregistered email | Error: "Email not found" |
| TC_014 | Dashboard Display | Load dashboard with existing user data | Display budget, expenses, and investments |
| TC_015 | Third-Party Integration | Connect bank account via Plaid API | Successful authentication and account linking |
| TC_016 | Third-Party Integration | Use incorrect bank credentials | Error: "Invalid login details" |
| TC_017 | Report Export | Request monthly financial report | PDF/CSV file downloaded |
| TC_018 | Multi-Factor Authentication | Enable MFA and verify login | Successful login after OTP verification |
| TC_019 | Role-Based Access Control | Admin tries to change user role | User role updated successfully |
| TC_020 | Role-Based Access Control | Unauthorized user tries admin actions | Error: "Permission denied" |
