<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />




<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Roles configuration
- Departments configuration
- Teams configuration
- Agents and Users configuration
- SLA configuration
- Help Topics configuration

<h2>Configuration Steps</h2>
The first step would be to open your osTicket virtual machine and sign in to osTicket as an admin. After this, you want to create the "supreme admin" role. To do this go to the admin panel, select agents, and select roles. Then click Add New Role and name the role supreme admin and proceed to check ALL permissions. Once your roles are created, go ahead and create your departments. Click Admin Panel, Agents, Departments, and click Add New Department. All you need to do is make sure the parent is set to top-level department and name it SysAdmins, from there you can go ahead and create it.

<p>
<img src="https://i.imgur.com/qyJNU5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/CXC9hXf.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/MAi0zxc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
You can now create your teams by clicking admin panel, agents, and click teams. Click Add New Team, name it Online Banking, and create it. You should also make sure anyone can create tickets, you can do this by clicking Admin Panel, Settings, User Settings, and make sure "Require registration and login to create tickets" is unchecked. After this, you should create your agents. Click on Admin Panel, Agents, Add New, and proceed to name the agent Jane Doe, and give them a fake email. Make sure to set her password as "Password1", put her into SysAdmins as a supreme admin, and put her into the online banking team. After her, make a new agent named John Doe and do the same you did with Jane, except for his department, which should be Support with All Access and you don't need to put him into any teams.
<p>
<img src="https://i.imgur.com/w3GFxkg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/GetCBzd.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/zyRlyTJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/NiV50Sc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

</p>
<p>

</p>
<br />
You should now create your user, which can be done by clicking Agent Panel, Users, Add New, then name the user Karen, give them a fake email, and create the user. After this, you should create your SLA's which can be done by clicking Admin Panel, Manage, SLA, and clicking Add New SLA Plan. You should create three SLA's, Sev-A, Sev-B, and Sev-C. Sev-A should have a one-hour grace period with a 24/7 schedule, Sev-B with a four-hour grace period with a 24/7 schedule as well, and Sev-C with an eight-hour grace period with Business Hours set as the schedule. Once that is done, you should create your help topics, which can be done by clicking Admin Panel, Manage, Help Topics, and Add New Help Topic. You should create five help topics, "Business Critical Outage" with "Report a Problem" as the parent topic, "Personal Computer Issues" with "Report a Problem", "Equipment Request" with "General Inquiry", "Password Reset" with "Report a Problem", and finally "Other" with "General Inquiry". Once that is done, you have finished the post-installation setup!
<p>
<img src="https://i.imgur.com/WCMoiHT.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/J7bHlPk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/bYRRjPU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/OIaerMl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/spBecDA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/J35vToq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/xmDqOqW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/obqd9om.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/i3Mim1x.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

</p>
<br />
