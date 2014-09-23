### Chapter 3: Use Cases and User Flow

#### 1. Students 

Students are the primary user group of our application. They will use the software to gain points based on attendance and challenge completion (as awarded by the indoor-positioning system that tracks their attendance. They can also spend points to improve their keep. Special rewards would be awarded to the highest-performing students (get an exam question or topic beforehand etc.).

Note that the login to the application would be different if used in the classroom, as classroom mode would automatically log in every student with the correct privileges that happened to stay close enough to the indoor beacon.

#### 2. Teachers 

Teachers can use the software to track students' participation in the game, assign challenges, and punish/reward students based on performance (though rewards could be automated).

#### 3. Developers/admins

Developers/admins use the software to monitor and collect data. Fix bugs as reported by other users and add additional features.

#### Use case diagram

<img src="http://users.metropolia.fi/~jonisarj/coa_usecases.png" alt="use cases">

#### Use case cenarios

##### 1. Student

###### Initial state:
 * Student chooses to view available points and to spend them if possible.

###### Normal flow:
 * Application accepts the request, shows student the available points and all possible targets they can spend points on. Student selects an upgrade to purchase and the system awards that upgrade instantly, crediting the user's account with it.

###### Failure states:
 * Application can't contact the database or server for the user's account, failing the request to show points. Application could also fail to update the user's upgrade purchase to his/her account. Clear error messaging is an absolute must.

###### Other activities:
 * Application processing a multitude of requests from several users. Point totals being updated constantly.

###### End state:
 * Student either views the point total and stops using the application or purchases an upgrade successfully and then logs out. 

##### 2. Teacher

###### Initial state:
* The teacher chooses to assign a challenge to one course group.

###### Normal flow:
* The system complies to the request and brings up a list of all course groups under the teacher's supervision and upon selecting one, brings up a list of all possible challenges. These challenges would vary depending on the archetype of the course. Once the challenge is selected, the system would show a message saying "Challenge assigned", and then the students of that course would be able to see the challenge on their side.

###### Failure states:
* No courses are visible for the teacher. No possible challenges can be assigned for whatever reason. Once the challenge is selected, the system could fail to assign it to the group. The system might also fail to show the assigned challenge on the students' end (a myriad of frightening failure states then).

###### Other activities:
* Other teachers are assigning challenges at the same time. Students are viewing the application front end on their side and attempting complete challenges.

###### End state:
* Challenge is successfully assigned for completion, teacher logs out.

#### Use case flow chart

<img src="http://users.metropolia.fi/~jonisarj/coa_flowchart.png" alt="flow chart">
