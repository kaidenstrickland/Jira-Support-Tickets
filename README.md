<h1>Jira Support Tickets</h1>

<h2>Objective</h2>
The objective of this lab was to simulate common Tier 1 Help Desk problems. By utilizing Active Directory and Windows administrative tools from my Active-Directory Lab environment, I aimed to restore user productivity through efficient troubleshooting of identity management and account access.
<br />

<h2>Project Summary</h2>
In this lab, I raised and responsed to 2 support tickets. These included a password reset and an account unlock. I was about to learn how to conduct these tickets and document/work through the Jira environment.
<br />

<h2 align="center">📝Ticket 1: Password Reset</h2>


- <b>Issue Description:</b> User could not access their account due to forgetting their password.
<br /><br />

- <b>Resolution:</b> Reset the user’s password via Active Directory Users and Computers (ADUC). Issued a temporary password and enabled "User must change password at next logon" to ensure account security. 
<br /><br />

- <b>Technical Takeaway:</b> I learned how to manage user identities in AD, enforce credential security policies, and document resolutions in Jira. I also realized the importance of input precision. Verifying temporary passwords prevents secondary lockouts caused by misinputs which would negatively affect customer experience and support efficiency.
<br /><br />


<div align="center">
  <h2>Ticket Walkthrough</h2>
</div>
<br />
<p align="center">
<img width="600" height="200" alt="image" src="https://github.com/user-attachments/assets/a9bafa4b-25ff-4e64-9960-11384d3ff9a1" />
<p align="center">
<b>Password Reset Received through Jira Interface</b>

<p align="center">
<img width="613" height="232" alt="image" src="https://github.com/user-attachments/assets/d9b84554-c5a5-488b-8fe0-205e30490b9b" />
<p align="center">
<b>Reviewing the details of the ticket and any relevant information</b>

<p align="center">
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/be4e83eb-476e-4503-a713-4d949586111b" />
<p align="center">
<b>Located the user (Alane Dove) through ADUC search</b>

<p align="center">
<img width="395" height="269" alt="image" src="https://github.com/user-attachments/assets/63d77de0-f171-4b94-a5df-ef60efd4b361" />
<p align="center">
<b>Reset password to “NDomain*” and required a password change upon login</b>

<p align="center">
<img width="329" height="157" alt="image" src="https://github.com/user-attachments/assets/a7347a50-371c-4c21-9e6d-f43c3268e139" />
<p align="center">
<b>Confirmation Message</b>

<p align="center">
<img width="500" height="348" alt="image" src="https://github.com/user-attachments/assets/c1ddabbb-d770-4bef-b6a8-cfac9e05f141" />
<p align="center">
<b>Communicating the process completion to the user</b>

<p align="center">
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/6adaf9ec-0cba-46ed-ac19-d11d8116117d" />
<p align="center">
<img width="400" height400500" alt="image" src="https://github.com/user-attachments/assets/eb997e2d-66ca-470e-a3c2-50a5918cc8e6" />
<p align="center">
<b>Login successful and user prompted for new password</b>


<p align="center">
<img width="500" height="585" alt="image" src="https://github.com/user-attachments/assets/7e53f423-ad44-410f-b528-7fe34443b50f" />
<p align="center">
<b>Ticket Resolution and Closure</b>
<br />
<br />

<h2 align="center">🔒Ticket 2: Account Lockout</h2>


- <b>Issue Description:</b> User could not access their account due to repeated incorrect login attempts resulting in an account lock.
<br /><br />

- <b>Resolution:</b> Unlocked the user’s account through Active Directory Users and Computers and reviewed the rules associated with account lockouts.  
<br /><br />

- <b>Technical Takeaway:</b> I learned how to manage account locks through AD, adjust the threshold for incorrect login attempts, and the duration of user lockouts to ensure network security.
<br /><br />


<div align="center">
  <h2>Ticket Walkthrough</h2>
</div>
<br />
<p align="center">
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/19566535-a33c-4543-be86-a4d2dcd79a04" />

<p align="center">
<b>Account lockout ticket received through Jira </b>

<p align="center">
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/20229cd5-3cfe-4535-8531-1c492c47f4a9" />
<p align="center">
<b>Attatched screenshot of the user's experience</b>

<p align="center">
<img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/ad81bad0-99cc-483c-bc1a-1b5d9c7f8902" />
<p align="center">
<b>Located the user (Dawn Kim) through ADUC search and enabled her account unlock</b>

<p align="center">
<img width="500" height="432" alt="image" src="https://github.com/user-attachments/assets/7b237e46-af91-45f8-859d-362d6c1cfdda" />
<p align="center">
<b>Communicating the process completion to the user</b>

<p align="center">
<img width="508" height="378" alt="image" src="https://github.com/user-attachments/assets/e3daca5a-87ab-42a7-834d-1c669da22efe" />

<p align="center">
<b>Successful login from user account</b>

<p align="center">
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/fa5993da-2833-4bb8-bfe8-fa7390241c2f" />
<p align="center">
<b>Review of account lockout settings</b>

<p align="center">
<img width="500" height="404" alt="image" src="https://github.com/user-attachments/assets/211ec63d-00a0-4c4c-919c-73cf601cdcf7" />
<p align="center">
<b>Ticket completion and resolution</b>



