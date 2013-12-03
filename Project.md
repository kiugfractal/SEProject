<h1>Introduction</h1>
<h2>Project description</h2>
<p>The system provides more features to help users communicate easier, by focusing on the friend networking by ID. Therefore, every user can go through his own group (group ID) or chat with others. One is able to update his own status or upload media files, or track his friend’s position.</p>
<h2>System description</h2>
<p>This system is targeted to Metropolia students and teachers, in order to create a convenient and dynamic communication environment.</p>
<p>The system will be built on 2 main sides:
<ul>
<li>The front-end: the layout, user interface where the users interact with the app.</li>
<li>The back-end: where the server will receive and process data from the users.Beside, this is where application retrive and store data in database.</li>
</ul></p>
<p>For deployment, the core code of application is stored on univerisity server and users can access to application as a web application.</p>

<h1>Use cases</h1>
<h2>User group overview</h2> 
<p>In the system, there are two user groups: normal user (teachers, student...) and system admin group.  For the teacher and student group, they can login using Metropolia ID and will be sort into specific group based on their role on Metropolia ID. One is available to go and check any group’s status, members or uploaded contents.<p>

<p>As for system admin group, this user's role is to manage the whole system both in content and technical aspect of the application. System admins have ability to manipulate content of users from normal user group. Beside, they also have total control of system so if any problems happen, it will be convenient for them to work on that.</p>
<h2>Use case</h2> 
![my Flow chart](usercase.png)


<h2>Use case scenario</h2> 

<h4>Use case: Chat </h4> 
<ul>
<li>Initial state</li>
<li>Normal flow: choose friend -> begin to chat -> exit </li>
<li>Branching:If friend is not online, user can choose other one to chat or decide to send an offline message to friend</li>
<li>Other activities: recieve message from other </li>
<li>End state </li>
</ul>

<h4>Use case: Upload content </h4> 
<ul>
<li>Initial state</li>
<li>Normal flow: choose content to upload -> upload -> content appear on application. </li>
<li>Branching:If content format is wrong, system will ask to user to input again.</li>
<li>Other activities: validating upload content </li>
<li>End state </li>
</ul>

<h4>Use case: Login </h4> 
<ul>
<li>Initial state</li>
<li>Normal flow: Login -> Username/Password ok -> main page </li>
<li>Branching:If wrong password or username, prompt to ask email for reseting password</li>
<li>Other activities: None </li>
<li>End state </li>
</ul>

<h4>Use case: Edit Content</h4> 
<ul>
<li>Initial state</li>
<li>Normal flow: Choose content -> Edit content -> Confirm edit -> exit </li>
<li>Branching:User can forfeit editing by not confirm then exit</li>
<li>Other activities: None </li>
<li>End state </li>
</ul>


<h4>Use case: View  </h4> 
<ul>
<li>Initial state</li>
<li>Normal flow: Login -> Username/Password ok -> main page </li>
<li>Branching:If wrong password or username, prompt to ask email for reseting password</li>
<li>Other activities: None </li>
<li>End state </li>
</ul>

<h1>System architecture</h1>

<h2>Overview</h2>
![System Arch](systemarch.png)


<h4>Presentation tier</h4>
<p>In this tier, application provides visual interface of web application to the end-users. Everything is rendered as web application so HTML, CSS and javascript are the the best combination for this task.</p>

<h4>Logic tier</h4>
<p>This is where requests from presentation tier are processed. Additionally, logic tier makes queries to data tier to get data and response back to presentation tier to render that information on screen to end user.</p>

<h4>Data tier</h4>
<p>This is where data records are stored. Only get interact with logic tier.</p>


<h2>Main Modules</h2> 

<h4>Application module</h4> 

<h4>Chat module</h4> 


<h1>Requirements</h1>

<h1>User Interface</h1>

<h1>Project management, self reflection</h1>

