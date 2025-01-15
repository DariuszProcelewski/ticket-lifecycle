<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Ticket Lifecycle Stages</h2>

- Intake
- Assignment and Communication
- Working the Issue
- Resolution

<h2>Lifecycle Stages</h2>

Creating and Managing a Ticket (End-User and Agent Workflow)

![Screenshot 2025-01-15 160018](https://github.com/user-attachments/assets/654a799f-1ef3-44f9-b97c-538c1e8a82e6)

1) As an end-user, create the following ticket:
   
![Screenshot 2025-01-15 160846](https://github.com/user-attachments/assets/6cd52c84-da33-4a0d-9b7b-63be6776150f)
![image](https://github.com/user-attachments/assets/65f1a843-765e-4ea3-b6e1-105297a2c6d0)

3) Login as A Help Desk agent named John. http://localhost/osTicket/scp/login.php
   
   ![image](https://github.com/user-attachments/assets/31d5a965-8e74-4041-bbcd-97e83d062a10)
   
 As a Help Desk Agent (john), observe the ticket’s properties

- Priority
 
- Department
 
- SLA
 
- Assigned To
  
  ![Screenshot 2025-01-15 161522](https://github.com/user-attachments/assets/e6020249-04d3-4788-ab9f-b3733976b71e)
![Screenshot 2025-01-15 163320](https://github.com/user-attachments/assets/da9d06a8-6cec-4edd-b2d8-96b8fc367b29)

3) Set Properties to the ticket

- Sev-A (1 hour, 24/7)
  
  ![Screenshot 2025-01-15 163857](https://github.com/user-attachments/assets/404b7c89-83ff-47e8-9d36-8019cb8df761)

- Correct "Help Topic" as issue have wide impact on bussines
  
![Screenshot 2025-01-15 164317](https://github.com/user-attachments/assets/f27c00f2-7aa7-455d-bdb1-6632bb112f27)

- Assign to Online Banking Department
  
![image](https://github.com/user-attachments/assets/1d6b0820-659c-4714-8cdf-f9bc0e4980b2)

Work the ticket to completion as jane

![Screenshot 2025-01-15 165344](https://github.com/user-attachments/assets/7f03ab3c-df0e-4083-925f-a516d34fb7cf)
![Screenshot 2025-01-15 165641](https://github.com/user-attachments/assets/d9d32fd5-0a46-458e-8054-e26a14787f74)
![image](https://github.com/user-attachments/assets/625ad47c-5a20-4314-a93a-743b75335e77)
![Screenshot 2025-01-15 170144](https://github.com/user-attachments/assets/1870c5cf-840f-4f08-b36d-be8cafeef362)

Effective communication is key when resolving tickets. It’s essential to maintain clear communication with both your team and the affected users. Tickets vary in nature, are assigned to different team members, and require proper management. For instance, John handled a ticket assigned by Jane, while Jane independently managed another ticket. Proper documentation is vital for maintaining an efficient workflow, as it allows tickets to serve as references for similar issues in the future.

Ticket management protocols can vary based on the work environment. Some workplaces may set quotas for the number of tickets to be resolved within a specific timeframe, while others prioritize tickets based on urgency and impact. Through building osTicket from the ground up, I gained valuable insight into how ticketing systems function in an IT role and how they support issue resolution.
