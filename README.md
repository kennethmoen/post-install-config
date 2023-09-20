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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA 
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/IASfKnE.png"/>
</p>
<p>
Go to the help desk login page with the link below and begin configuring you Osticket system by configuring the various functions as described in the Post-Install Configuration Objectives in the above list.<br \>
<a href="http://localhost/osTicket/scp/login.php"> Ticket Login Page </a>
</p>
<br />

<p>
<img src="https://i.imgur.com/rswPKKV.png"/>
</p>
<p>
Click on the Admin Panel and then click on agents and roles to get to this page and then click add new role. Create the Supreme Admin role and give it all permissions.
</p>
<br />

<p>
<img src="https://i.imgur.com/ZMANqnF.png"/>
</p>
<p>
Go back to the Agents Panel and then click on Departments and create the System Admistrators Department. 
</p>
<br />

<p>
<img src="https://i.imgur.com/Yyq1Ipr.png"/>
</p>
<p>
Go back to the Agents panel again and click on the Agents tab to create a new Agent that is part of the System Administrators Department.
</p>
<br />

<p>
<img src="https://i.imgur.com/sGgVgeS.png"/>
</p>
<p>
From the Agents Panel go to teams and create Level II Support and add the agent you created to that team.
</p>
<br />

<p>
<img src="https://i.imgur.com/Jaf0v7S.png"/>
</p>
<p>
Click on the Agents Panel on the top right and click on Users and click on create new user to create two new users.
</p>
<br />

<p>
<img src="https://i.imgur.com/yi1HSPl.png"/>
</p>
<p>
From the Admins Panel go to manage and then SLA to configure SLA. Add three SLAs with these schedule and grace periods: <br \>
SEV-A (24/7, 1 hour) <br \>
SEV-B (24/7, 4 hours)<br \>
SEV-C (Business Hours, 8 hours)<br \>
</p>
<br />

<p>
<img src="https://i.imgur.com/TE9bhRO.png"/>
</p>
<p>
Go back to manage and then configure these 4 help topic:<br \>
Business Critical Outage<br \>
Personal Computer Issues<br \>
Equipment Request<br \>
Password Reset<br \>
Be sure to go to ticket information and be sure to set the SLA and priority accordingly. This concludes the Osticket Post Installation setup demonstration.

</p>
<br />
