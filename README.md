<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# osTicket - Post-Install Configuration

This guide covers the post-install setup of the open-source help desk ticketing system osTicket.

## Environments and Technologies Used

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- osTicket

## Operating Systems Used

- Windows 10 (21H2)

## Post-Install Configuration Objectives

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents & Users
- Configure SLA and Help Topics

## Configuration Steps

<p>
  <img width="656" alt="image" src="https://github.com/user-attachments/assets/a53444c2-8a25-435e-a9e2-caa1c7fcb74e" />
</p>
<p>
After installing osTicket and logging in with admin credentials, you’ll land on the Admin Panel. To set up roles, go to Agents -> Roles. Rename an existing role or click "Add New Role" to create one. I renamed an "All Access" role to "Supreme Admin" with full permissions. For departments and teams, click their tabs (Agents -> Departments or Teams) and configure as needed - e.g., a "SysAdmins" department and an "Online Banking" team.
</p>
<br />

<p>
<img width="665" alt="image" src="https://github.com/user-attachments/assets/246a7bcb-7b31-4b1f-98f1-ecacdf61847a" />
</p>
<p>
To let anyone submit tickets without registering, go to Admin Panel -> Settings -> Users -> uncheck "Require registration and login to create tickets". For stricter control, check it and require login instead.
</p>
<br />

<p>
<img width="653" alt="image" src="https://github.com/user-attachments/assets/3f97306d-d5e0-410e-86fe-2e7b26617e12" />
</p>
<p>
To add agents (workers), go to Admin Panel -> Agents -> Add New. Create an agent like "Jane" under the Account tab, then set her department (e.g., SysAdmins), access, and teams in their respective tabs.
</p>
<br />

<p>
  <img width="681" alt="image" src="https://github.com/user-attachments/assets/1418add2-7e62-4d75-9e29-f9b33a5462a7" />
</p>
<p>
To add users (customers), switch to the Agent Panel by clicking it in the top-right corner. Then go to Users -> Add New, fill in details for someone like "Karen", and save.
</p>
<br />

<p>
  <img width="656" alt="image" src="https://github.com/user-attachments/assets/43ea3728-aa1c-4038-a222-68db119560f1" />
</p>
<p>
For Service Level Agreements (SLAs), return to the Admin Panel -> Manage -> SLA -> Add New SLA Plan. Set up one like "Sev-A" with a 1-hour grace period and 24/7 schedule, then click "Add Plan". Repeat for others like "Sev-B" (4 hours, 24/7) or "Sev-C" (8 hours, business hours).
</p>
<br />

<p>
  <img width="673" alt="image" src="https://github.com/user-attachments/assets/31f4e2b9-8af3-454c-adec-f5961e9f7573" />
</p>
<p>
Finally, set up Help Topics to categorize tickets. Go to Admin Panel -> Manage -> Help Topics -> Add New Help Topic. Add options like "Business Critical Outage", "Personal Computer Issues", or "Password Reset", setting their priority and department as needed.
</p>
<br />
