#Introduction
##Project description
The system provides more features to help users communicate easier, by focusing on the friend networking by ID. Therefore, every user can go through his own group (group ID) or chat with others. One is able to update his own status or upload media files, or track his friend’s position.
##System description
This system is targeted to Metropolia students and teachers, in order to create a convenient and dynamic communication environment.

The system will be built on 2 main sides:


*The front-end: the layout, user interface where the users interact with the app.
*The back-end: where the server will receive and process data from the users.Beside, this is where application retrive and store data in database.

For deployment, the core code of application is stored on univerisity server and users can access to application as a web application.

#Use cases
##User group overview
In the system, there are two user groups: normal user (teachers, student...) and system admin group.  For the teacher and student group, they can login using Metropolia ID and will be sort into specific group based on their role on Metropolia ID. One is available to go and check any group’s status, members or uploaded contents.

As for system admin group, this user's role is to manage the whole system both in content and technical aspect of the application. System admins have ability to manipulate content of users from normal user group. Beside, they also have total control of system so if any problems happen, it will be convenient for them to work on that.
##Use case
![my Flow chart](usercase.png)


##Use case scenario 

####Use case: Chat####
-Initial state
-Normal flow: choose friend -> begin to chat -> exit 
-Branching:If friend is not online, user can choose other one to chat or decide to send an offline message to friend
-Other activities: recieve message from other 
-End state 


####Use case: Upload content####

Initial state

Normal flow: choose content to upload -> upload -> content appear on application. 

Branching:If content format is wrong, system will ask to user to input again.

Other activities: validating upload content 

End state 


####Use case: Login

Initial state

Normal flow: Login -> Username/Password ok -> main page 

Branching:If wrong password or username, prompt to ask email for reseting password

Other activities: None 

End state 


####Use case: Edit Content 

Initial state

Normal flow: Choose content -> Edit content -> Confirm edit -> exit 

Branching:User can forfeit editing by not confirm then exit

Other activities: None 

End state 

####Use case: View Group's network

Initial state

Normal flow: Choose group -> upload contents or chat with users in the group

Branching:Teacher's upload contents are always in pin post
Other activities: None 

End state 


####Use case: Track Other's Location

Initial state

Normal flow: Choose location section -> Friends' locations appear

Branching:If check-in button is clicked, user's location will be seen by friends

Other activities: None 

End state 


####Use case: Create User

Initial state

Normal flow: Choose Add User -> Write user's info -> confirm

Branching: Grant priviliges to users for helping admins manage the application 

Other activities: None 

End state 


####Use case: Delete content

Initial state

Normal flow: Choose delete content -> click button delete -> exit

Branching: Admin could delete contents by dragging them to the trash box

Other activities: None 

End state 


####Use case: Ban User

Initial state

Normal flow: Click ban user -> write reason ->confirm

Branching: Banning user in the limited of time or forever 

Other activities: None 

End state 




#System architecture

##Overview
![System Arch](systemarch.png)


####Presentation tier
In this tier, application provides visual interface of web application to the end-users. Everything is rendered as web application so HTML, CSS and javascript are the the best combination for this task.

####Logic tier
This is where requests from presentation tier are processed. Additionally, logic tier makes queries to data tier to get data and response back to presentation tier to render that information on screen to end user.

####Data tier
This is where data records are stored. Only get interact with logic tier.


##Main Modules 

####Application module

####Chat module


#Requirements ##Functional requirements Users can communicate each other by chat section and check people’s location Users can see Pictures, videos and other media files can be shared. Status can be updated in real-time, school’s group lists are categorized. Adminstrator can manage users' account Administrator can manage all the uploaded content

##Non-functional requirements

####Usability The application should be easy to use, and the navigation buttons must be clear to locate in the header for example “Back button” to get back to the previous section must be large and easy to recognize. Moreover, it should have just 1 tap to login, 2 taps to see and comment in updated contents. The application

####Efficiency
We limit the file size to improve the processing speed to make users' experience better The layout is simple to help new users use the application easier Functions like 'Search' or 'Help' are placed in the front layout in order to help the user

####Reliability The admin of the system is “well trusted” so that user can update everything they want or share, talk about with their friends with no leaked information. It is quite important to have the back-up server to prevent the sudden accident that could cause low loading or even crash down the whole application The users' information is protected and sercured by system

####Other non-functional requirements Speed: The application should be smooth, fast in every devices (especially mobile by J query Mobile Flexibility: Application can run with full function on all major browsers PC and mobile: Chrome, Firefox, Safari (on IE) Portability: The application run on a server so user can connect throw the net from anywhere.

#User Interface

#Project management, self reflection
Hello this from my branch

