## Final Lab Task 2 - Transform ER into Relational tables
Given the ER diagram representing student assignment submissions, convert it into MySQL
tables. Capture all entities and their attributes, and define the relationships between students,
submissions, and assignments. Identify the primary and foreign keys and ensure proper
representation of any dependent or weak entities.

# In converting the ER diagram, 
 _The following are the data types of the attributes:_

  
* **student table:**
> username: String (VARCHAR), up to 50 characters.

> ![Sample Output](IMAGE/task%202/1.PNG)

* **assignment table:**
> shortname: String (VARCHAR), up to 50 characters.\
due_date: Date, cannot be null.\
url: String (VARCHAR), up to 255 characters, can be null

> ![Sample Output](IMAGE/task%202/2.PNG)

* **submission table:**
> username: String (VARCHAR), up to 50 characters.\
shortname: String (VARCHAR), up to 50 characters.\
version: Integer, represents the version of the submission.\
submit_date: Date, cannot be null.\
data: Text.

> ![Sample Output](IMAGE/task%202/3.PNG)

# *EER*
![Sample Output](IMAGE/EER%20task%202.PNG)



