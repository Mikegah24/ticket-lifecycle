<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

# ticket-lifecycle

Admin/Analyst Login Page:
http://localhost/osTicket/scp/login.php 

End Users osTicket URL:
http://localhost/osTicket 

In this lab, we will be creating tickets as end users
Observing all the ticket properties and responding to them as help desk professionals

  - Change the SysAdmins Department to a Top Level Department
  - DELETE the Maintenance Department (not archive)

DELETE the Maintenance Department (not archive)


As an end-user, create the following ticket
entire mobile/online banking system is down

![image](https://github.com/user-attachments/assets/6dc2e405-8bb3-45e8-a482-a6366cfe4ab5)
![image](https://github.com/user-attachments/assets/43566513-72a7-40c9-99bc-836171910557)



- As a Help Desk Agent (john), observe the ticket’s properties
  
	  Priority
	  Department
	  SLA
	  Assigned To
 
![image](https://github.com/user-attachments/assets/850f2953-ff4f-4681-a93d-0e5fa46881cb)
![image](https://github.com/user-attachments/assets/e87963a0-ea5c-4079-aac4-652819b3cf66)

Set Properties to the ticket
  - Sev-A (1 hour, 24/7)
  - Online Banking Department
![image](https://github.com/user-attachments/assets/5dc322cd-a9fa-4d24-8d9c-e8945f54e523)

Attempt to observe the ticket again as “john”. Can you view or change?

- Work the ticket to completion as `jane`

![image](https://github.com/user-attachments/assets/aa4c9a05-b3e4-4e80-ac84-2fc50984ef13)


As an end-user, create the following ticket
  `accounting department needs adobe upgrade, broken`

As a Help Desk Agent (john), observe the ticket’s properties
	  Priority
  	Department
	  SLA
	  Assigned To

Set Properties to the ticket
  - Sev-B (4 hours, 24/7)
  - Support

Work the ticket to completion as `john`

![image](https://github.com/user-attachments/assets/e6a8063c-e18f-4181-9e7b-61ebb9b46fdb)
![image](https://github.com/user-attachments/assets/99f0aacb-35a1-4620-9292-ce8cd98c2456)


As an end-user, create the following ticket
CFO’s laptop will no longer turn on

As a Help Desk Agent (john), observe the ticket’s properties
  	Priority
  	Department
	  SLA
	  Assigned To

Set Properties to the ticket
  - Sev-B (4 hours, 24/7)
  - Support

Work the ticket to completion as `john`
![image](https://github.com/user-attachments/assets/05b80122-4685-40e0-9b56-3e8e476204be)


- Set Properties to all the tickets; do SEV-A (SysAdmins last), observe ticket becomes inaccessible
- Switch to admin panel and assign yourself View-access to Sys Admins
- Switch to agent panel and observe the escalated ticket
- Observe that you can no longer make changes to it

Solve all of the tickets
- Explain in most ticketing systems (probably this one too) there is an email capability so every time you update the ticket, the user gets a copy and they can respond

Explain ticket intake IRL:
- Sometimes tickets get created via phone, chat app, email, web form, or maybe even you run into someone in your hall or they roll up on you at your desk.
A lot of the time people will randomize you and try to get you to fix stuff on the spot. It’s fine to fix things on the spot, but generally speaking, you want to create tickets for EVERYTHING you do. (metrics are important)

- Finishing up and additional practice
- Obviously there is much more to this product that covered here
- Encourage the use and exploration of the email feature
- Do this lab a few more times, enough times where you’re able to implement it with this simple checklist. This will build your intuition.

