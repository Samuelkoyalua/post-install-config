<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)



<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/5IL2LwM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
1. Access Admin Panel: Log in to the administrative panel of the system.
2. Navigate to Agents Section: Within the Admin Panel interface, locate and click on the "Agents" option. This typically serves as the hub for managing user roles, departments, and teams.</p>



3.Configure Roles:
Click on the "Roles" subsection under the "Agents" menu.
In the Roles section, add a new role titled "Supreme Admin". This role will likely have elevated permissions and control over various aspects of the system.



4.Configure Departments:
Still within the "Agents" section, find and select the "Departments" subsection.
Here, you'll define specific organizational units or departments. Create a department labeled "System Administrators". This department could encompass users responsible for managing and maintaining the system infrastructure.
<br />



5.Configure Teams:
Remaining in the "Agents" section, proceed to the "Teams" subsection.
Create teams to categorize and organize agents based on their responsibilities and expertise.
Create a team named "Level I Support" to handle initial support queries or basic troubleshooting tasks.
Create another team called "Level II Support" for more complex or specialized support issues that require escalated attention or expertise.

<p>
<img src="https://i.imgur.com/CNi14cc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next we'll allow everyone to create tickets,  
Access Admin Panel: Log in to the administrative panel of the system.
Navigate to Settings: Locate and click on the "Settings" option within the Admin Panel interface.
Access User Settings:
Within the Settings menu, find and select the "User Settings" section.
Enable Registration Requirement:
Look for the setting titled "Registration Required".
Toggle the setting to "Require registration and login to create tickets".</p>
<br />

<p>
<img src="https://i.imgur.com/n8ddLQO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Next. Access Admin Panel: Log in to the administrative panel of the system.
Navigate to Agents Section:
Locate and click on the "Agents" option within the Admin Panel interface.
Add New Agents:
Select the "Add New" option within the Agents section.
Input Agent Information:
Enter the details for each new agent:
For example, add "Jane" as a new agent by filling in her information.
Similarly, add "John" by providing his details.</p>
<br />








<p>
<img src="https://i.imgur.com/x8gqG6A.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>


Next Configure Users (customers). Access Agent Panel: Log in to the agent panel interface.
Navigate to Users Section:
Locate and click on the "Users" option within the Agent Panel interface.
Add New Users:
Select the "Add New" option within the Users section.
Input User Information:
Enter the details for each new user:
For instance, add "Karen" as a new user by providing her information.
Similarly, add "Ken" by filling in his details.







<p>
<img src="https://i.imgur.com/el45iMb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>



Configure SLA. Access Admin Panel: Log in to the administrative panel of the system.
Navigate to SLA Management:
Locate and click on the "Manage" option within the Admin Panel interface.
Access SLA Configuration:
Select the "SLA" option to access the SLA management settings.
Define SLA Levels:
Define SLA levels and their respective response times:
Create an SLA level named "Sev-A" with a response time of 1 hour, applicable 24/7.
Establish another SLA level labeled "Sev-B" with a response time of 4 hours, also applicable 24/7.
Lastly, set up an SLA level called "Sev-C" with an 8-hour response time, applicable during business hours.








<p>
<img src="https://i.imgur.com/WsqCfCL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

Configure Help Topics:

Access Admin Panel: Log in to the administrative panel of the system.
Navigate to Help Topics Management:
Locate and click on the "Manage" option within the Admin Panel interface.
Access Help Topics Configuration:
Select the "Help Topics" option to access the Help Topics management settings.
Define Help Topics:
Create the following Help Topics:
"Business Critical Outage"
"Personal Computer Issues"
"Equipment Request"
"Password Reset"

That should be it folks, congrats!! ✔️
