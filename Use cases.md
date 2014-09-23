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
 * Student uploads files to return an assingment and clicks "Return to teacher".

###### Normal flow:
 * System accepts the student's assignment, uploads it to the server and shows a message saying "Upload successful". Teacher can then check and grade the assignment on their end.

###### What can go wrong:**
 * System fails to upload attached files to the server. System fails to return the assingment successfully, showing an error message (e.g. deadline passed), the user can then choose to back out of the use case or try again.

###### Other activities:
 * Messages displayed, showing the user what is happening at each state of the return process.

###### End state:
 * Assignment returned successfully; system shows a message informing the user of that fact.


* Main use cases described more in detail, based on a template
  * a template: initial state, normal flow, end state
  * a template also tells how a use case can fail
  * in addition, you can describe alternative flows of the case
* Choose one of the use case templates and describe it as a flow chart
