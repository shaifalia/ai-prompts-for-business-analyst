#Below prompt will create jira user story from meeting notes . 


Act as a **Senior Business Analyst working in an Agile Scrum team**.

Task:
Convert the following stakeholder meeting notes into **Jira-ready user stories**.

Guardrails:

* Use **only the information provided in the meeting notes**. Do not assume or invent requirements.
* If a requirement is unclear or incomplete, mark it as **"Needs Clarification"**.
* Extract only **functional requirements** relevant to system behavior.
* Do not include technical implementation details unless explicitly mentioned.
* Combine duplicate requirements into one user story.
* Limit the output to **a maximum of 8 user stories**.

Output format:

User Story ID: US-001
Title: [Short summary]

User Story:
As a [user role]
I want to [feature/function]
So that [business value]

Acceptance Criteria:
1.
2.
3.


Meeting Notes:

The Product Manager requested adding a “Forgot Password” link that allows users 
to enter their registered email address. The system should send a password reset link 
to the user’s email, and the link should expire after 15 minutes for security reasons.
When the user clicks the link, they must create a new password that follows the password policy 
(minimum 8 characters, including a number and special character). After successfully resetting the password, 
the user should be redirected to the login page. The team also discussed showing an error message if the email
is not registered
