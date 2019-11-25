Cloud Project (Problem no 12) 
===============================
Submission By: Ankush Rodewad(1701011), Sahil Jaiswal(1701058), Harsh Vishwakarma(1701025)

Please visit https://iiitg-connect.web.app to see and test this project

Problem statement: Create an access control mechanism in a public cloud, wherein the
identity is verified in the private cloud and is federated.

Description: This project is an extention to IIITG-Connect (Complaint redressal system for
	IIITG). We have developed a web app which lists the registered complaints. There
	are two roles [Faculty] and [Student]. Faculty can access all the registered 
	complaints whereas Student can access only the complaints registered by him/her.
	Authentication is done through "Firebase Authentication API" and access control is
	implemented in the web application.

How this works:
 - Authenticate with email id and password
 - Click on "list complaints" button.
 - If you are authorised as a Faculty in database of "IIITG-Connect", you will
   be able to list all the complaints registered by students.
 - If you are authorised as a student in database of "IIITG-Connect", you will
   be able to list only the complaints registered by you.



 - If you sign up instead of signing in, a verification link will be sent to you,
   verify your email and then you will be assigned a the role of student by default.

 - Faculty role is assigned by the administrator manually by modifying the database.
 - Ferdous sir has been assigned the role of Faculty in the database.