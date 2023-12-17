<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Configuration Steps</h2>

<p>
Now that OsTicket has been installed, we will be doing post installation setup.  First, we will create a new role.  On the Admin panel, click on Agents at top, then Roles, and then Add New Role.  On the new role, check all the permissions.  Roles are the permissions granted to Agents, per the Department that they have access to.
</p>

<p>
<img src="https://i.imgur.com/LjoD4tV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Next, we will create a new department by clicking on Agents, then Departments, and name it "System Administrators". 
</p>
<br />

<p>
<img src="https://i.imgur.com/jLMznOB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Next, we will create a new Team.  Click on Agents, then Teams, and Add New Team.  Name it "Level II Support".  We want to allow anyone to be able to create tickets.  We do this in the Admin panel by clicking on Settings, and then Users.  Then check the box marked "Require registration and login to create tickets".
</p>
<br />

<p>
<img src="https://i.imgur.com/ac3Q1en.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
<img src="https://i.imgur.com/BlnnG2g.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Next, we will create agents.  Agents are the employees in an organization that will respond to the tickets that are created.  In Admin panel, click on Agents and then Add New Agents.  We can then add any name that we want.
</p>
<br />

<p>
<img src="https://i.imgur.com/8I9g13z.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<p>
Now, we can configure the SLA (Service Level Agreements).  SLA provides the length of time in which the tickets are expected to be viewed, corrected, and then closed.  In the Admin panel, click on Manage, and then SLA, and then Add New SLA.  We have created three new SLA plans.
</p>
<br />


<p>
<img src="https://i.imgur.com/vSglrHQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>


<p>
Finally, we configure the Help Topics. These are used to help users categorize their tickets. In Admin panel, click on Manage, and then Help Topics, and finally Add New Help Topics.  We will add the following Help topics: Business Critical Outage, Personal Computer Issues, Equipment Reset, and Password Reset.
</p>
<br />

<p>
<img src="https://i.imgur.com/n67ieu2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<br />
