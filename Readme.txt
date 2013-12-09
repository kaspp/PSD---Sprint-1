------
README
------

This is a command line program, where Teaching Administrators should be able to export the selected course data as a CSV file, and upload this data to other University information systems. And Tutors should be able to record attendance of students at a particular session, and this data will be stored for university records.

Teaching Administrators are also able to edit, delete, import, and manually insert the grades into the system. They are also allowed to view either all courses' grades or single course's grades.

Other than the functions stated above for Tutors, they are also able to import, edit, delete, export, view, and manually mark the students' attendance.


-----------------
BRIEF DESCRIPTION
-----------------

1. Main.java

	-Launch the user login screen.
	-Validate the login credentials.
	-If successful, it prints the the menu according to the user type by calling the printUI method from the respective java class.
	-If unsuccessful, an error message will be shown and user will have to key in their login credentials for validation again.

2. StudentAttendance.java

	-Displays the list of options/functions that user can use.
	-Validates all user inputs when needed.
	-Calls up the respective methods according to the option input by user.

3. tutorLoadGrade.java

	-Displays the list of options/functions that user can use.
	-Validates all user inputs when needed.
	-Calls up the respective methods according to the option input by user.


----------
HOW TO RUN
----------

To run this program, the following three java files are required:

	1. Main.java
	2. StudentAttendance.java
	3. tutorLoadGrade.java

Firstly, using command prompt, navigate to the directory where all the java files stated above are stored.

To confirm whether the required files are inside the directory that you are currently working at, run the command "dir", to list all files in your current working directory.

Next, compile the Main.java file using the following command:
"javac Main.java" 

To run these java files use the following command:
"java Main"

Finally, you can either login and navigate according to the list of options displayed on the screen.


-------------
DOWNLOAD LINK
-------------

To download, please refer to the link below:

		http://bit.ly/188aimF

-------
CONTACT
-------

If you have any problems, questions, ideas or suggestions, please contact us by sending an email to 2110002L@student.gla.ac.uk.

------
NOTICE
------

This program is done by Team Source Code © 2013. All rights reserved.