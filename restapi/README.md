# This is a students restapi built using golang as backend and mysql as database.

## APIs

### http://localhost:8080/students => GET
### http://localhost:8080/student/id => GET
### http://localhost:8080/student/id => POST
### http://localhost:8080/student/id => UPDATE
### http://localhost:8080/student/id => DELETE


## POSTMAN INSTRUCTIONS:
### FOR INSERTION OF DATA SEND JSON FORMAT IN THE BODY PART OF AS BELOW => POST METHOD:

{"id": "18157", "name": "Sayali Thakur","age": "23", "dept": "Comp Sci", "subject": ["Software Devlopement-II","DevOps"]}

### FOR UPDATION OF DATA SEND JSON FORMAT AS BELOW===> UPDATE METHOD
{"id": "existing id", "name": "WantToUpdate","age": "WantToUpdate", "dept": "WantToupdate", "subject": ["Software Devlopement-II","DevOps","WantToUpdate"]}

WantToUpdate => is new values which you want to update.


### DEPENDENCY:
1) Docker

### HOW TO RUN PROJECT?
##### 1) You just clone or download the project into you host machine.
##### 2) Change the mode of run.sh file by using command ===> chmod +x run.sh
##### 3) Execute command ./run.sh
##### 4) When you get one prompt then just execute ./startup.sh
