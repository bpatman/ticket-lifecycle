<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Ticket Lifecycle: Intake Through Resolution</h1>
This tutorial outlines the lifecycle of a ticket from intake to resolution within the open-source helpdesk ticketing system osTicket.<br/>


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

<h3>Stage 1: Intake</h3>


- Open osTicket
- Select Open a New Ticket
- Email Address: <a href='#' style='text-decoration: none; color:#000000'>jason@osTicket.com</a>
- Name: Jason Jason
- Help Topic Dropdown Menu: Business Critical Outage
- Issue Summary: Entire mobile online banking is down
- Details: Customers are reporting they are getting a 404 error when browsing to online banking
- Create Ticket

<p align="center">
<img src="https://github.com/user-attachments/assets/ee22b072-5dcf-4e17-af8c-16dc0dcbb464" height="70%" width="70%" alt="Azure Free Account"/> 
<img src="https://github.com/user-attachments/assets/c8364ba4-5232-4178-8c1a-77c5611fd5c8" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Assignment and Communication</h3>

- Sign into osTicket as an Agent 
- We created justin.here in the previous tutorial, log in with those credentials.
- Select the ticket that was created in the previous step.
  
  
<p align="center">
<img src="https://github.com/user-attachments/assets/80917e72-ff2a-4538-8b6b-8b388307c1b7" height="80%" width="80%" alt="Azure Free Account"/> 
</p>


- Priority: Emergency. 
- Mobile online banking down can lead to losses in revenue for the company. 
- Assigned to: Justin Here
- SLA Plan: SEV-A 
- Business impacting, critical incident
- Department: System Administrators 
- Sys Admins responsible for mobile banking infrastructure
- Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.
- Select Post Reply


<p align="center">
<img src="https://github.com/user-attachments/assets/470374aa-a392-4cf4-b4b3-7a02fbe81d77" height="80%" width="80%" alt="Azure Free Account"/> 
<img src="https://github.com/user-attachments/assets/e4210c40-735a-4214-849a-ec75a5cc94c1" height="80%" width="80%" alt="Azure Free Services"/>
</p>

<h3>Stage 3: Working the Issue</h3>

- Justin is working with the System Adminstrator team to resolve the issue. 


<h3>Stage 4: Resolution</h3>
     
- Once the issue is resolved, head back to the ticket and update the end user.
- Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up. 
- Ticket Status: Resolved
- Select Post Reply
- The ticket should now be on the "closed" tab since it has been resolved.

<p align="center">
<img src="https://github.com/user-attachments/assets/cfd59f95-dde7-4034-9a5d-2b276f82052a" height="80%" width="80%" alt="Azure Free Account"/> 
<img src="https://github.com/user-attachments/assets/19162ded-c260-45af-9e9d-d9406714da89" height="80%" width="80%" alt="Azure Free Services"/>
</p>



  
