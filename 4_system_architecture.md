### Chapter 4, system architecture

In this section we've tried to give you an overview of what our system's database would look like. Even though it is not the final version that could be built, this should give everyone a rough view of the necessary components of our application. In the diagrams below, you will note that the admin panel has the access all of the databases. This means that an admin can add or delete any user or remove their history at any time. This account is used for solving bugs or developing further improvements.

Only the Admin has access when adding new courses and assigning them to different groups. Students will see the course only if they enroll on it; this way it will collect each and every student's data and will keep crediting their attendence until the course is over.

The most important part of the system is the "Classes". Generally a single classroom will hold several courses during a semester, so the class' positioning system will receive student attendance records for specific courses. Should the course location or time change, the databse will be modified accordingly for all students. The database would only respond to the students that are assigned to that course (no matter what group, though teacher could also change this rule if he wanted to). It will start collecting data when it has found a device connected to its network. In order to avoid conflicts with other class networks, an anti jamming hub will we used, so the students won't face any trouble as long as they are inside the class.

Whenever the class' IPS finds familiar devices it will start the countdown for that specific user to track out when and how long the device was connected. As soon as the lecture's time slot ends, it will save the data for that account so that the teacher and student both have the access to the records.

Another view of our system is the teachers' section, in which teachers can only see their courses and the students' attendance records. The teacher can send notifications to specific students if they so choose, and that notification will be shown for that student on their side of the application.Only Teacher can choose courses and can change classes if necessary.

Another section is the student or user section. Here the students can see all of their enrolled courses and attendance records as well as notifications about classes.

 <img src="http://i62.tinypic.com/i5z0a0.png" alt="SA">

### Databases :

Here we have few databases; such as Class, Students, Teachers, Group, Course, etc. to keep all user data separate and viewable only to those with the correct access levels.


