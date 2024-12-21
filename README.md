<img src="https://i.imgur.com/tUnlhRz.jpeg" height="80%" width="80%" alt="Setting Up in Azure"/>

# osTicket: Ticket Lifecycle Management and Troubleshooting

This project showcases a hands-on approach to understanding and managing ticket lifecycles in a professional IT environment, including creating, escalating, and resolving tickets as a support engineer/admin. It emphasizes troubleshooting, adhering to SLAs, and ensuring proper ticket management to meet organizational objectives. Highlights the dual perspectives of ticketing systems and demonstrates proficiency in resolving real-world IT issues like an IT wizard.🫡

!!IMPORTANT !!

Whenever I refer to creating tickets as an end user im using this portal http://localhost/osTicket 

Whenever I refer to solving or anything as an admin/ support engineer im using this portal http://localhost/osTicket/scp/login.php 
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
<h2>Step 1: Create a ticket as an end user</h2>

- Navigate to the end user site of osTicket (http://localhost/osTicket/scp/login.php) to create a new ticket

<img src="https://i.imgur.com/KJiMJCt.png" height="80%" width="80%" alt="Setting Up in Azure"/>


- Open three new tickets and fill out the users information along with the technical issues
<img src="https://i.imgur.com/NNkxqMh.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<img src="https://i.imgur.com/3PG2u21.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<img src="https://i.imgur.com/be7cLS4.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 2: Review ticket as an admin</h2>

- Log in as an agent (admin) we created ((http://localhost/osTicket/scp/login.php) 
<img src="https://i.imgur.com/OQN9UEx.png" height="80%" width="80%" alt="Setting Up in Azure"/>

 - All the open tickets we created should be visible in the "Tickets" tab
<img src="https://i.imgur.com/rMVO4Vh.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- Clicking on a ticket allows you to see all the information about the ticket; It's priority, SLA, 
creation date, and more

<img src="https://i.imgur.com/HzAHuH9.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- Change the priority level to an appropriate level by clicking the "Priority" section 

- Alwayds add a note for amy changes made

<img src="https://i.imgur.com/5zHCxWa.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 3: Assign ticket </h2>

- To assign a ticket, click on "Unassigned" next to the "Assigned To" section - > select an agent to assign this ticket to

<img src="https://i.imgur.com/jBistCZ.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 4: Assign ticket SLA </h2>

- Change the tickets SLA (Service Level Aggrement) in the "SLA Plan" section

<img src="https://i.imgur.com/wnQbU4T.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 5: Assing tickets to a department r</h2>

- Assogn tickets department in the "Department" section

<img src="https://i.imgur.com/Yg3aPgm.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 6: Observe ticekts and changes made </h2>

- Navigate further down you can see a thread of all of the changes made to the ticket

<img src="https://i.imgur.com/e3n5j2T.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- At the bottom we can post replies communicating updates of the ticket

<img src="https://i.imgur.com/TGV2OUw.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- If we go back to see all the open tickets, we can see the changes we made to the ticket

<img src="https://i.imgur.com/xCvfP6b.png" height="80%" width="80%" alt="Setting Up in Azure"/>

<h2>Step 7: Resolve a ticket</h2>

- To resolve a ticket, navigate and select "Resolved" from the "Ticket Status" menu at the bottom of the ticket

<img src="https://i.imgur.com/4GuIshR.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- All resolved tickets will disappear from the open tickets tab 

<img src="https://i.imgur.com/FwlbkJK.png" height="80%" width="80%" alt="Setting Up in Azure"/>

- And appear in the closed tickets tab

<img src="https://i.imgur.com/tva9bvR.png" height="80%" width="80%" alt="Setting Up in Azure"/>


# 🎉Congratulations
osTickets now has users and have the know how to do our ticketing needs. Don't forget, be the tech wiz you know you can be. Kepp on Keeping on 🧙‍♂️ 

<h2>We Have Successfully:</h2>

- Created and resolved tickets while familiarizing ourselves with ticket lifecycles.

- Observed and applied SLAs, priorities, and departmental workflows.

- Allocated tickets to appropriate departments and handled ticket escalations efficiently.

- Followed and adjusted SLAs based on ticket priority and class to meet organizational needs.

- Developed troubleshooting skills by addressing real-world ticketing scenarios.

# That Concludes all osTicket labs  <img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="30px"/>
