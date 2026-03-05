#this prompt will create a flow chart from unstructured data which is stakeholder meeting notes.paste this prompt in lucid ai
you are a business analyst 

Analyze the following unstructured stakeholder meeting notes and generate a flowchart for the user login workflow.

Instructions:

1. Extract the key steps involved in the login process.
2. Arrange the steps in the correct sequence from start to end.
3. Identify decision points such as credential validation or OTP verification.
4. Include error handling paths when login fails.
5. Remove duplicate or irrelevant information.
6. Convert the structured steps into a clear flowchart with:

   * Start event
   * Process steps
   * Decision diamonds
   * End states
7. Ensure the workflow represents a secure login process.

Stakeholder Meeting Notes:
The user first opens the application login page. The application displays a login form.
The user enters username and password and clicks login.
The system sends credentials to the authentication service for verification.
The authentication service checks credentials against the user database.
If the credentials are incorrect the system shows an error message and the user can try again.
If credentials are correct the authentication service triggers multi-factor authentication.
An OTP is generated and sent to the user’s registered device.
The user enters the OTP in the application.
The system verifies the OTP.
If OTP verification fails the user is prompted to retry OTP entry.
If OTP verification succeeds the system creates a user session and redirects the user to the dashboard.

Expected Output:
Generate a structured flowchart that includes process steps, decision points, and success/failure paths for the login workflow.
