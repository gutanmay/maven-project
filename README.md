# maven-project
DEVOPS LAB 4
#PERFORMING BELOW TASK
•	Task 1: Create a Source Code Repository in GIT.

•	Task 2: Create a build in Jenkins (To complete this perform below points)
a)	Set Git, JDK HOME & Maven installation path in Jenkins Global Tool Configuration
b)	Import GitHub Plugin
c)	Create a New Job in Jenkins
d)	Set your created Git Repo URL under Source Code Management of Jenkins project
e)	In add build step click on “Invoke Top Level Maven Targets”, and Provide name of local Maven Installation
f)	Set the goal for Maven as “Clean Package” [Note: This is Maven build life cycle]
g)	Build this Job and Observe the Console output

•	Task 3: Perform Continuous Integration (To complete this perform below points)
a)	Open the Created Job in Task 2 in Jenkins
b)	Click on “Configure tab” and under “build trigger” select “Poll SCM” & type “* * * * *” for Schedule [Note: This is cron job Syntax]
c)	Save the Job & Observer Git Pull log

•	Task 4: Perform continuous integration through Jenkins by modifying source code in Git Repository
