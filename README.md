<img src="https://i.imgur.com/tUnlhRz.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>

# osTicket: Ticket Lifecycle Management and Troubleshooting

This project showcases a hands-on approach to understanding and managing ticket lifecycles in a professional IT environment, including creating, escalating, and resolving tickets as a support engineer/admin. It emphasizes troubleshooting, adhering to SLAs, and ensuring proper ticket management to meet organizational objectives. Highlights the dual perspectives of ticketing systems and demonstrates proficiency in resolving real-world IT issues like an IT wizard.🫡

!!IMPORTANT !!

Whenever I refer to creating tickets as an end user im using this portal http://localhost/osTicket 

Whenever I refer to solving or anything as an admin/ support engineer im using this portal http://localhost/osTicket 
<h1>osTicket: Post-Installation Configuration</h1>


<h2>Tools & Technology Used</h2>

- osTicket: A widely-used open-source ticketing system for customer support.
- Microsoft Azure: Cloud platform for hosting the Windows 10 virtual machine.
- Windows 10 VM: Virtual environment used for hosting and configuring the ticketing system.
- RDP: Remote Desktop Protocol for securely accessing the Azure-hosted VM.

- Networking Protocols; ICMP, SSH, RDP, DNS, DHCP

<h2>Key Objectives:</h2>

- Gain practical experience with ticket lifecycles, SLAs (Service Level Agreements), and priority handling.
- Learn to create tickets as an end user and resolve them as a support engineer.
- Allocate tickets to the appropriate department and manage escalations effectively.
- Troubleshoot and resolve tickets while adhering to SLA guidelines.
- Familiarize with adjusting SLAs based on ticket priority and class to optimize support workflows.



<h2>Prerequisites</h2>

- osTicket: Prerequisites and Installation
- osTicket: Configuring Departments, Agents, Users, Roles, and Permissions

- A fully functioning osTicket instance hosted on a Microsoft Azure Windows 10 Virtual Machine.

# Project Overview
<h2>Step 1: Access Admin Configuration Panel</h2>
<p align="center">
First, I will navigate to the end user site of osTicket to be able to create a new ticket: <br/>
<img src="https://i.imgur.com/KJiMJCt.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I will open three new tickets and fill out the users information along with the technical issues:  <br/>
<img src="https://i.imgur.com/NNkxqMh.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/3PG2u21.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/be7cLS4.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Next, I will log in as an agent (worker) we created:  <br/>
<img src="https://i.imgur.com/OQN9UEx.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I can now see all the open tickets I created in the "Tickets" tab:  <br/>
<img src="https://i.imgur.com/rMVO4Vh.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
When clicking on a ticket I can see all the information about the ticket like its priority, SLA, creation date, and more:  <br/>
<img src="https://i.imgur.com/HzAHuH9.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I can change the priority level on appropriate tickets by clicking the "Priority" section and can add a note for the change made:  <br/>
<img src="https://i.imgur.com/5zHCxWa.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To assign a ticket, click on "Unassigned" next to the "Assigned To" section and select an agent to assign this ticket to:  <br/>
<img src="https://i.imgur.com/jBistCZ.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
I can also change the tickets SLA (Service Level Aggrement) of the ticket in the "SLA Plan" section:  <br/>
<img src="https://i.imgur.com/wnQbU4T.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Another option I have is to change the tickets department in the "Department" section:  <br/>
<img src="https://i.imgur.com/Yg3aPgm.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
Looking further down I can see a thread of all of the changes made to the ticket:
<img src="https://i.imgur.com/e3n5j2T.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
At the bottom I can post replies communicating updates of the ticket:  <br/>
<img src="https://i.imgur.com/TGV2OUw.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
If I go back to see all the open tickets, I can see the changes I made to the ticket:  <br/>
<img src="https://i.imgur.com/xCvfP6b.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
To resolve a ticket, I can select "Resolved" from the "Ticket Status" menu at the bottom of the ticket:
<img src="https://i.imgur.com/4GuIshR.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
The resolved ticket will disappear from the open tickets tab and appear in the closed tickets tab:
<img src="https://i.imgur.com/FwlbkJK.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />
<img src="https://i.imgur.com/tva9bvR.png" height="80%" width="80%" alt="Setting Up in Azure"/>
<br />
<br />

<b> We've successfully gone through the life cycle of a ticket from creation to resolution, made changes to the tickets when necessary like assigning the tickets, changing the SLA (Service Level Agreement), and commenting to create a thread of clear communication! </b>

# 🎉Congratulations

<h2>We Have Successfully:</h2>

- Created and resolved tickets while familiarizing ourselves with ticket lifecycles.
- Observed and applied SLAs, priorities, and departmental workflows.
- Allocated tickets to appropriate departments and handled ticket escalations efficiently.
- Followed and adjusted SLAs based on ticket priority and class to meet organizational needs.
- Developed troubleshooting skills by addressing real-world ticketing scenarios.

# That Concludes this lab, osTicket is up and running and fully configured for use 🌝. In the next lab we will create tickets and resolve them as a support engineer. Familarizing ourselves with ticket life cycles, SLA, and GOOD 'OL TROUBLESHOOTING🤓. <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
