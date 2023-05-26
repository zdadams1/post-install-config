<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket Guide - Post Installation Setup Guide (Part 2 of 3)</h1>
This part outlines the post-install configuration of osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration</h2>

 - Configure Roles
    Admin Panel -> Agents -> Roles Supreme Admin
    <img src="https://https://i.imgur.com/xtE0uBm.png" alt="supadmin"/>
    <img src="https://i.imgur.com/FUZEQCc.png" alt="supadmin"/>
    <img src="https://i.imgur.com/OKxVnWX.png" alt="supadmin"/>
 - Configure Departments
    Admin Panel -> Agents -> Departments System Administrators
    <img src="https://i.imgur.com/hd63jn4.png" alt="departments"/>
 - Configure Teams
    Admin Panel -> Agents -> Teams
      Level I Support
      Level II Support
      <img src="https://i.imgur.com/0sT5Lo4.png" alt="teams"/>
 - Allow anyone to create tickets
    Admin Panel -> Settings -> User Settings
    Registration Required: Require registration and login to create tickets 
    <img src="https://i.imgur.com/LEJNBoK.png" alt="anyonetickets"/>
 - Configure Agents (workers)
    Admin Panel -> Agents -> Add New
      Jane
      John
      <img src="https://i.imgur.com/u94VVun.png" alt="newagent"/>
 - Configure Users (customers)
    Agent Panel -> Users -> Add New
      Karen
      Ken
      <img src="https://i.imgur.com/tLbMxaK.png" alt="newuser"/>
 - Configure SLA
    Admin Panel -> Manage -> SLA
      Sev-A (1 hour, 24/7)
      Sev-B (4 hours, 24/7)
      Sev-C (8 hours, business hours)
      <img src="https://i.imgur.com/ktGUH34.png" alt="sla"/>
      <img src="https://i.imgur.com/e2oV3dX.png" alt="sla"/>
 - Configure Help Topics
    Admin Panel -> Manage -> Help Topics
      Business Critical Outage
      Personal Computer Issues
      Equipment Request
      Password Reset
      <img src="https://i.imgur.com/PFglqau.png" alt="helptopic"/>
<br />
<a href="https://github.com/zdadams1/ticket-lifecycle">osTicket Lifecycle</a>
<br />
