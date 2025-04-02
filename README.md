<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post Installation and Configuration</h1>
This tutorial outlines the post installation of the open-source help desk ticketing system osTicket and it's configurations.<br />


<h2>osTicket Website</h2>

- ### [osTicket Installation Files](https://docs.osticket.com/en/latest/Getting%20Started/Installation.html)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Configure roles to group permissions
- Configure departments
- Configure teams
- Adjust user settings
- Configure agents
- Configure users
- Configure SLA
  

<h2>Installation Steps</h2>


![Screenshot 2025-04-01 234200](https://github.com/user-attachments/assets/2bac7af1-126b-42ea-909d-486fa999b0a9)

<p>
To set up the system, start by configuring roles to group permissions. First, navigate to the Admin Panel, then go to Agents, and select Roles. Here, create a role called Supreme Admin. Next, configure departments to manage ticket visibility, such as separating Help Desk, SysAdmins, and Networking. To do this, go to the Admin Panel, then Agents, and select Departments. Create a department named SysAdmins. After that, configure teams by pulling agents from different departments. Head to the Admin Panel, then Agents, and select Teams. Set up a team called Online Banking.
</p>
<br />


![Screenshot 2025-04-01 235104](https://github.com/user-attachments/assets/a786c102-fffc-48d7-b067-d2683402353b)

<p>
To ensure anyone can create tickets only after registering, adjust the user settings. Go to the Admin Panel, then Settings, and select User Settings. Uncheck the option that says "unregistered users can create tickets" and enable the setting that requires registration and login to create tickets. Now, configure agents, who are the workers. Navigate to the Admin Panel, then Agents, and choose Add New. Add an agent named Jane, assigning her to the SysAdmins department, and add another agent named John, assigning him to the Support department.
<br />


![Screenshot 2025-04-01 235454](https://github.com/user-attachments/assets/018cc4c6-f885-4770-9f4c-f19c98a36384)

<p>
Next, configure users, who are the customers. Go to the Agent Panel, then Users, and select Add New. Add a user named Karen, followed by another user named Ken. After that, configure the Service Level Agreements, or SLA. Head to the Admin Panel, then Manage, and select SLA. Create an SLA called Sev-A with a grace period of 1 hour and a 24/7 schedule. Then, create Sev-B with a grace period of 4 hours and a 24/7 schedule. Finally, create Sev-C with a grace period of 8 hours and a schedule limited to business hours.
</p>
<br />


![Screenshot 2025-04-01 235942](https://github.com/user-attachments/assets/eb4efcec-6d84-4895-85e6-db29eafbff77)

<p>
Lastly, configure help topics for when users create tickets. Go to the Admin Panel, then Manage, and select Help Topics. Add a help topic called Business Critical Outage. Then, add another called Personal Computer Issues, followed by Equipment Request, Password Reset, and Other. By following these steps, you’ll have the system configured with all the necessary roles, departments, teams, settings, agents, users, SLAs, and help topics.
</p> 
<br />

