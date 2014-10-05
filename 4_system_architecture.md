### Chapter 4, system architecture

In this section we've tried to give you an overview of what our system's database would look like. Even though it is not the final version that could be built, this should give everyone a rough view of the necessary components of our application. In the diagrams below, you will note that the admin panel has the access all of the databases. This means that an admin can add or delete any user or remove their history at any time. This account is used for solving bugs or developing further improvements.

Only Admin has the access on making new course and assign them with different classes.Students will see the course only if they enroll them so that it will collect each and every student data enrolled to it and will keep counting their attendence until it's finish date.

The most important part is the "Classes".Generally a single classroom arrange a couple of courses during whole semester.So the classes gps will only receive data during specific course is held.And when there is time for different courses at some other time,it will change it's database according to that courses as well as assigned students.It will only responds to those devices which is assigned to that course (No matter what group it will be,though teacher can also change this rule if he want to).It will start collecting data when it found a device connected to it's network and to avoid conflicts with other class network, an anti jamming hub will we used,so the students won't face any troubles as long as he is inside the class.

Whenever the class gps find familiar devices it will start the countdown for that specific device to track out when and how long the device was connected and as soon as it's time end it will save the data for that account so that the teacher and student both have the access of his presence. 

Another view of our system is the teachers' section, in which teachers can only see their courses and the students' attendance records. The teacher can send notifications to specific students if they so choose, and that notification will be shown for that student on their side of the application.Only Teacher can choose courses and can change classes if necessary.

Another section is the student or user section. Here the students can see all of their enrolled courses and attendance records as well as notifications about classes.

 <img src="http://i62.tinypic.com/i5z0a0.png" alt="SA">

### Databases :

Here we have few databases; such as Class, Students, Teachers, Group, Course, etc. to keep all user data separate and viewable only to those with the correct access levels.


