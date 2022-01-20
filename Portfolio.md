# Portfolio
This is the document in which I document the thought process and decision making behind the products I produce whilst working towards the learning outcomes for semester 3.

## About Raccool
Raccool is the project in which I will work towards the learning outcomes for the individual project. <br>

This project consists of a web application built with React and a backend built with Springboot and Kotlin. <br>
Data persistency will be achieved through the use of SQL databases. <br>

The aim of the web application is create a place where users can find raccoons that they like and add them to their 'raccoon collection'. The raccoons will be randomly generated using data stored in a database. When a user adds a racoon to their collection this collection will also be stored in a database for data persistency.

#### Why React?
React is a popular library used for frontend development. Because of this popularity it is a valuable library to gain experience with. <br>
Another benefit of using React is that React also allows you to build user interfaces relatively quickly, the learning curve isn't very steep. <br>
The final reason to use React is that the component based design is something I find very appealing.

#### Why Kotlin?
Kotlin came recommended to me by a friend who works as a senior developer. <br>
Kotlin's ability to integrate with java code and its handling being more similar to languages such as C# were listed as reasons. <br>

As I have experience with C# this made Kotlin an appealing choice.

#### Why SQL?
The data intended to be stored within this project is small and very few relations will exist. Because of this scalability will be unlikely to become an issue. <br>
Because of this I do not expect noSQL to give me significant benefits over SQL.

## Beginning of the project
User stories were made and are visible on the project board.

### C4 Diagrams

#### C1
info about c1 diagram

![C1 diagram](/portfolio_images/Raccool_C1_Context_Diagram.drawio.png)

#### C2
info about c2 diagram

![C2 diagram](/portfolio_images/Raccool_C2_Containers_Diagram.drawio.png)


## Learning outcomes

### 1. Web Application

For web application I build a react SPA that could communicate with services.
This web application used React for the frontend and Kotlin with JPA in the backend.

As services I used RaccoonService and HobbyService.
Raccool requests raccoons from RaccoonService

RaccoonService requests a hobby from hobbyservice and a name from randommer.io, an external api.

RaccoonService returns raccoons to raccool.

### 2. Software Quality

For software quality I utilised code reviews in the group project. 
In addition for the IPS I wrote tests verifying user stories.

### 3. CI/CD

For CI/CD I setup actions in git to automaticaly run checks on branches which need to pass before a merge/push. this can be found in raccool.
Docker is also used to automaticaly deploy a docker container. Which is done automaticaly through gitactions in raccool.

### 4. Professional

For professional development I focused on the project board, in which I logged issues and the status of the issue. Furthermore I can see which issues are linked to which pull request

I also focused on what's known as the GitHub flow. This means that to work on a feature you'd: create a branch of the desired branch to work on, make changes, make a pull request back to the desired branch, have it reviewed, merge, delete the branch your own branch.

Finally I started work on research. This research is about social engineering and how it circumvents traditional security measures.
