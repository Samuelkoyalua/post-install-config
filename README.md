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
