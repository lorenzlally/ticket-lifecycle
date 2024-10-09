# ticket-lifecycle

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

<h3>Stage 1: Intake - Creating a Ticket</h3>


- Open osTicket
- Select Open a New Ticket
  - Email Address: <a href='#' style='text-decoration: none; color:#000000'>karen@osTicket.com</a>
  - Name: Karen Karen
  - Help Topic Dropdown Menu: Business Critical Outage
    - Issue Summary: Entire mobile online banking is down
    - Details: Customers are reporting they are getting a 404 error when browsing to online banking
  - Create Ticket

<p align="center">
<img src="https://i.imgur.com/G7Ak6uI.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/UdiPc1s.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>Step 2: Assignment and Communication</h3>

- Sign into osTicket as an Agent
  - We created jane.doe in previous tutorial, log in with those credentials. 
  - Select the ticket we created in Step 1.
  
  
<p align="center">
<img src="https://i.imgur.com/sDgzS36.png" height="80%" width="80%" alt="Azure Free Account"/> 
</p>


 - Priority: Emergency. 
      - Mobile online banking down can lead to losses in revenue for the company. 
 - Assigned to: Jane Doe
 - SLA Plan: SEV-A 
      - Business impacting, critical incident
 - Department: System Administrators 
      - Sys Admins responsible for mobile banking infrastructure
 - Response text box: Coordinating with Sys Admin Team to bring mobile banking back online.
    - Select Post Reply


<p align="center">
<img src="https://i.imgur.com/Du3kmui.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yg9TXep.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>

<h3>Stage 3: Working the Issue</h3>

- On the back end, Jane is working with the System Adminstrator team to resolve the issue. 


<h3>Stage 4: Resolution</h3>
     
- Once the issue is resolved, head back to the ticket and update the end user.
  - Response text box: Jerry from System Engineering found and connected a failed load balancer. Mobile banking should be back up. 
  - Ticket Status: Resolved
- Select Post Reply
- The ticket should now be on the "closed" tab since it has been resolved.

<p align="center">
<img src="https://i.imgur.com/et8h651.png" height="80%" width="80%" alt="Azure Free Account"/> <img src="https://i.imgur.com/TUo3T0Q.png" height="80%" width="80%" alt="Azure Free Services"/>
</p>


🎉Congratulations! You have created and resolved your first ticket!🎉
  
