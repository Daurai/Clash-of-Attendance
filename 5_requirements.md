## Functional and Non-Functional Requirements

####Functional Requirements

Functional requirements are a description of what a software should be able to do, relating to specific use case scenarios. There are two main use cases for this application: students and teachers. Both will have slightly different functional requirements.

######Functional Requirements for Students

1. Login function - login with student crdentials is required to access the application, as this also serves as verification of the students' identities.
2. WiFi connection - Wireless connection to the school's wireless network (and thereby the indoor positioning system) will be established after students have logged in successfully.
3. Fetching course information - after logging in and connecting to the wireless network successfully, the application will fetch the personal course information for every student, displaying a timetable for the day with information such as classroom number and lesson times.
4. Displaying map to classrooms - the application would then use the indoor positioning system to guide the students to their classrooms. This would be especially helpful for students who are new to the school, and do not yet know the locations of each classroom.
5. Attendance logging - as soon as the student is in range of the appropriate WiFi beacon corresponding to the classroom s/he is meant to be in, the application would start logging attendance and storing it to the application's server.
6. Scoring system - based on a student's attendance rates, the system will alert students if they are eligible for a reward based on their performance.

######Functional Requirements for Teachers

1. Login function - teachers also need a login function for identity verification.
2. WiFi connection - after successful login, the wireless connection is needed to be able to view the information the the application stores.
3. Fetching course information - after successful login and wireless connection, the application will fetch the information relating to the courses being taught by the teacher, as well as the names and student numbers of the students attending each course.
4. Student attendance records - shows the teacher the attendance rates of each student.
5. Assigning rewards or punishments - teachers can assign rewards and punishments to students based on their attendance, as well as assign new rewards as goals to be reached through proper attendance.

####Non-Functional Requirements

Non-functional requirements relate to how well a system functions, and creates a standard of quality for the funtional requirements to meet in order for the application to be satisfactory for users.

Wireless connection stability - obviously a stable, working wireless internet connection is required for the system to work properly, as the wireless network is the basis of the indoor positioning system which monitors students' attendance rates and creates maps for students.

Accuracy of the indoor positioning system - the size and positions of the classrooms should be accurately triangulated in the indoor positioning system inorder for the attendance logging to be hard to exploit by students.

Automatic login - in order to make matters simpler for users, the application could store 
