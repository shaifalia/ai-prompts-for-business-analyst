#Copilot prompt to generate lookup tool in new worksheets without manually writing formulas. 
#Open the excel data file before using this prompt.Ensure the excel file has same header names as in the prompt

You are a business analyst.

Create a new worksheet named "Login Lookup Tool".
In that sheet, build a clean lookup interface where:
- Cell B2 is used to enter a Login_ID.
- Below it, display the following fields automatically retrieved from the authentication dataset:
  User_ID
  Application_Name
  Region
  Login_Date
  Auth_Method
  MFA_Enabled
  Login_Status
  Response_Time_ms
  Failure_Reason
Use best-practice Excel formulas.
Add error handling so that if the Login_ID is not found, it displays "Login Not Found".

Format the sheet professionally with clear headers.
