# Grading-Management-System-Project

Project Title: Grading Management System

Course and Section: BSIT - 2A

Leader:
- Ceejay B. Feruelo
Members:
- Chris Folloso
- Ivee Guevarra
- Joshua Talato
- Rudy Vargas III

 
Front End - Design / UI / UX
-	Rudy Vargas (Supervisor)
-	Ivee Guevarra
-	Ceejay Feruelo
Front End Responsibilities
Responsive Design 
User Interface + User Experience 
Performance Optimization 

Back End - Program / Database / APIs
-	Chris Folloso (Supervisor)
-	Joshua Talato
Back End Responsibilities
Application Logic
Database Management + Data Processing
Security, Authentication, and Authorization

 
Project Objective: The Project aims to efficiently grading processes for students, profs, and admins.

Student Account:
•	-Login System Portal:
o	-Username
o	-Password
o	-Password Recovery
•	-Viewing of Grades:
o	-The Grades Table should have:
	-Student's ID
	-Student's Name
	-Course, Year, and Section
	-Academic Year
	-Subject Code/ID
	-Subject Title
	-Semestral Grades (Different Tables for Midterms and Finals)
	-Subject Professor

 
Faculty Account:
•	-Login System Portal:
o	-Username
o	-Password
o	-Password Recovery
•	-Grading System Table:
o	Course Taught:
	-Course ID and Title
	-Student ID and Name
	-Create / Edit / Update Grades
•	-Midterms Grades
•	-Finals Grades
•	-Semesteral Grades (Automatic Grade Conversion)
•	-Professor Remarks
•	-Generate Report:
o	-Faculty ID
o	-Faculty Name
o	-Department
o	-Academic Year

 
Administrator Account:
•	-Login System Portal:
o	-Username
o	-Password
o	-Password Recovery
•	-Encoding Courses Metadata (Has Access to Create Edit Delete Data):
o	-Subject Code
o	-Subject Name
o	-Curriculum Year
•	-Encoding Professor Metadata (Has Access to Create Edit Delete Data):
o	-Faculty ID
o	-Faculty Name
o	-Department
•	-Encoding Student Metadata (Has Access to Create Edit Delete Data):
o	-Student ID
o	-Student Name
o	-Course, Year, and Section
o	-Department


 
Work Progress (3 Weeks)
Deadline: December 4, 2024
First Week Goal (Nov. 14 - 20):
•	-Front End:
o	-Setup basic layout and navigation framework of the Application
	-Student Portal
	-Professor Portal
	-Admin Portal
o	-Apply Consistent Color Palette or Theme for the Application, Typography (Fonts), and a "style" to ensure a cohesive look
o	-Implementation of Basic Components such as Textboxes, Buttons, Panels, Navigation Links
	-Make Sure of the PROPER and CONSISTENT naming of objects
•	-Back End:
o	-Design Database Schema and create tables for:
	-Students (Should have Student Metadata like StudentID, StudentName, Course, Year & Section, etc.)
	-Professors (Should have Professor Metadata like ProfID, ProfName, Department, etc.)
	-Administrators (Should have Admin Metadata)
	-Grades (Should have StudentID, CourseID, Midterm Grades, Final Grades, Semestral Grades, Remarks, etc.)
	-Courses (Should have CourseID, CourseName, ProfID, Curriculum Year)
o	-Establish Connection and Relationships between tables:
o	-Implement CRUD for each major table

 
Second Week Goal (Nov. 21 - 27):
•	-Front End
o	-Complete the design and layout for each login portal:
	-Ensure each portal has its input fields (Username, Password), and buttons for Register, Password Recovery and Login
o	-Implement the Structure for viewing components
	-Grade Table for Students
	-Grading System for Faculty
	-Metadata for Admins to manage students, profs, and courses
•	-Back end
o	-Finalize the Database with necessary Data Validation and Integrity Checks
o	-Develop Authentication and Authorization on Login Portals
	-Implement Login Functionality
	-Setup Permissions on each portal
o	-Implement Core Functionalities
	-Implement Viewing Grades on Student Account
	-Implement Grading System on Professor Account
•	-Compute Course Grades based on Student's Records
•	-Compute Midterm and Final Grades based on Student's Course Grades
•	-Compute Semestral Grade based on Student's Midterm and Final Grades
•	-Grade Conversions
	-Implement Metadata management on Admins
 
Third Week Goal (Nov. 28 - Dec 4)
•	-Front End
o	-Finalize UI/UX:
	-Refine all Forms for Responsiveness
	-Add Smooth Transitions and User-Friendly Navigation
	-Complete all "styling" adjustments and ensure consistency in the design and theme
•	-Back End
o	-Finalize all Application Functionalities
	-Ensure Student Accounts can see and download Grades as intended
	-Ensure Professor Accounts can use Grading System as intended
	-Ensure Admin Accounts can access All Medata
•	-Both
o	-Begin Debugging to Identify and Resolve Issues in both user interface and functionality
o	-Checking Integration between front end and back end to ensure smooth data flow between the application and database
Fourth Week Goal (Dec. 5 - Dec 10)
•	-Both
o	-Conduct VERY thorough test runs for all user roles:
	-Ensure that Students cannot access Professor and Admin Pages
	-Ensure that Professor cannot access Student and Admin Pages
	-Ensure that Admin cannot access Student and Professor Pages
o	-Testing Grade Entries
o	-Login Verification
•	-Documentation of the Work
