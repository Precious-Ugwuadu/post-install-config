# Post-Installation-Config
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

<h2>Post-Install Configuration Objectives</h2>

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
  
![image](https://github.com/user-attachments/assets/1efe0cfc-995f-45d7-83cb-25ae2f0daf67)

![image](https://github.com/user-attachments/assets/e4b8043e-2685-42ee-a8ca-ad6b636bb228)

I started by creating user roles in osTicket, which are used to set permissions for agents. These roles determine what actions agents are allowed to perform, such as viewing tickets, replying to customers, or managing system settings. By assigning specific roles, I was able to control access levels across the help desk. For instance, I created a role called "Supreme Admin", which gives full access to all features and settings in the system, ensuring complete administrative control.

</p>
<p>

![image](https://github.com/user-attachments/assets/b0626139-f801-412e-be11-694f2611bf77)

After setting up roles, I moved on to creating a department in osTicket. Departments help organize and manage support tickets by grouping them based on the type of issue or area of expertise. For example, I created a department named "SysAdmin" to handle system administration-related requests. When a user submits a ticket, osTicket can automatically route it to the correct department based on the issue type. This ensures the right team sees the ticket quickly, which helps speed up response times and improves overall efficiency in handling support requests.

</p>
<br />

<p>
  
![image](https://github.com/user-attachments/assets/2be6c404-8f19-4f85-be1b-a098155d1a10)

![image](https://github.com/user-attachments/assets/fc92cd7c-6af3-4a7b-94b8-2014d01d754f)

I then set up a team in osTicket. A team is a group of agents who work together to manage and resolve tickets related to a specific function, service, or issue type. Teams are useful when you want to assign tickets to a group rather than just one department or individual, allowing for better collaboration and faster responses. For example, I created a team called "Online Banking", made up of agents who are specifically trained to handle issues related to internet banking. This setup ensures that tickets about online banking are directed to the right experts, improving both the quality and speed of support.

</p>
<p>

![image](https://github.com/user-attachments/assets/901d40f5-942d-4d8b-ab51-bd366e606c72)

After setting up the departments and teams, I added two agents, Jane and John Doe, to the osTicket system. Agents are the users responsible for responding to and resolving support tickets. Each agent was configured with a unique username and assigned to specific departments and teams based on their roles and expertise.

For example, I assigned the first agent to the "SysAdmins" department and included them in the "Online Banking" team. This means the agent will primarily handle technical support tickets related to system administration and online banking services.

The second agent was added to the "Support" department and placed in the "Level 1 Support" team. This agent will focus on handling general inquiries and basic troubleshooting tasks, acting as the first point of contact for users.

By assigning agents to the right departments and teams, the system ensures that incoming tickets are automatically directed to the appropriate personnel, streamlining the workflow and improving overall support efficiency.

![image](https://github.com/user-attachments/assets/b65dda65-b365-4a4d-8377-51d3372369ce)

Next, I created a user profile to represent an end-user who submits support tickets. This includes basic details like name and email, allowing the system to track requests, send updates, and maintain a support history for personalized and efficient service.

![image](https://github.com/user-attachments/assets/11b1467e-ae44-4b7f-b891-3b2889deaeed)

I then set up three Service Level Agreements (SLAs) to define how quickly support tickets should be acknowledged and resolved based on their urgency. Each SLA includes specific time frames for initial response and final resolution. For example, a high-priority ticket might require a response within 1 hour and resolution within 4 hours, while a low-priority ticket may have longer deadlines. These SLAs help ensure timely support and maintain consistent service standards across different types of issues.

</p>
<br />

<p>

![image](https://github.com/user-attachments/assets/22ddf6b8-c8b4-4756-9bfb-0bc5eb414446)

</p>
<p>
Lastly, I created several help topics to organize incoming support requests. Help topics act like categories that users can choose from when submitting a ticket, which makes it easier for them to describe their issue and faster for agents to handle it. For example, I included help topics like “Business Critical Outage,” “Personal Computer Issues,” “Equipment Request,” “Password Reset,” and “Other.” This setup helps ensure that each ticket goes to the right team and gets resolved more efficiently.
</p>
<br />
