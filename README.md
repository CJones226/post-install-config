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

- Configuring Roles
- Configuring Departments
- Configuring Teams
- Configuring Agents
- Configuring Users
- Configuring SLA
- Configuring Help Topics

<h2>Configuration Steps</h2>

<h1>Login</h1>
<h4>Logging into osTicket can be a little bit confusing in the beginning so if you are having difficulty, you can just follow along the pictures here, otherwise skip down to 'Configuring Roles'.</h4>
<p>
<h4>Step 1: Opening osTicket</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/1a8c8228-4839-4152-a0af-56d15b557fc7" height="60%" width="60%" alt"Disk Sanitization Steps"/>
</p>
<p>
Opening osTicket is relatively simple, you just have to click on this link on the main page of the website. Once done it will navigate to the following page, where you will click on 'sign in' in the upper right hand corner.
</p>
<p>
<h4>Step 2: Sign In</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/cb16f885-4603-4978-81de-00421c6e86d6" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<h4>Sign in as Agent</h4>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/aa4678ed-04c5-40c9-a0fc-54aa4a468746" height="60%" width="60%"
</p>
<p>
When you get to this page you will want to click on 'sign in' next to 'I'm an agent." Once you click on that you can sign in using the credentials you created before.
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/eeecc494-695b-452a-a755-251af410972b" height="60%" width="60%"
</p>

<h3>Configuring Roles</h3>
<p>
Within osTicket there is a plethora of roles that can be added and changed at any given time. For this example we are going to create the 'Supreme Admin' Role. This role will be exactly what you think it is. A user with the ability to do absolutely everything. First things first we have to get to the roles portion of the website, for that you will first have to go to the "Admin Panel" as shown below.
</p>
<p>
<h4>Admin Panel</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/f96760f4-3700-478b-b519-136e73b119b9" height="60%" width="60%"
</p>
<p>
Once that is done you can navigate to the Agent Panel Then Roles
</p>
<p>
<h4>Agent Panel</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/ad11b598-9037-48c6-8f7a-2c03df32dc7f" height="60%" width="60%"
</p>
<p>
<h4>Roles</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/863f10f8-450d-401c-8c30-68a33327bfa5" height="60%" width="60%"
</p>
<p>
Once there you can add the role 'Supreme Admin' obviously the permissions that this role will have will be all encompassing.
</p>
<p>
<h4>Add Role</h4>  
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/d9b92109-f6bd-45bf-832e-44e047da1565" height="60%" width="60%"
</p>
<p>
Once you click on that you can name it "Supreme Admin" then activate all permissions.
</p>
<p>
<h4>Permissions</h4>
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/856bbb87-fa7e-4d45-b2b3-9278f1b93418" height="60%" width="60%"
</p>
<p>
Once done you have successfully learned how to add new roles, and they are simple to remove.
</p>

<h3>Configuring Departments</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/b15365de-2e4d-4a3d-9fde-eed0578ed475" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring departments is just as simple as adding new permissions. You simply navigate to the 'Departments' section and add a new one. This is important, because not every issue can or should be handled by a single department.
</p>
<br />

<h3>Configuring Teams</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/22822660-6600-4f60-b70e-6e69c1ca21fa" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Teams is similar to the department tab but adds the ability to make severity teams within departments to deal with tickets that are more or less severe.
</p>
<br />

<h3>Configuring Agents</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/blob/main/New%20Agents.JPG?raw=true" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Within in the agents tab you will be able to add new agents that can be dispersed within the teams and departments. Here I added Jane Doe, and John Smith. Both emails matching their names @helper.com, as well as usernames being lowercase e.g. "janedoe"
</p>
<br />

<h3>Configuring Users</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/90fa2eb2-b5a8-40ed-9b5b-1941fc98dc82" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring users is how you add and remove people who have access to creating tickets. Say, someone in accounting, or sales. This is how you add those people, so that if they have a problem they can send the ticket directly to the system. Before you configure that, you will want to setup "Require Registration."
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/c3b76397-0b56-4862-9bb3-71e9c20a4f80" height="60%" width="60%"
</p>
<p>
I added these users with the email @needhelp.com
</p>
<br />

<h3>Configuring SLA</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/3d0e087c-c05c-4054-a674-0116b15992fb" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Service Level Agreements dictate the level of service that each ticket will require. For this session I created three new ones: Sev-A, Sev-B, and Sev-C. Each one has varying times and priorities. This is how each new ticket will be assessed.
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/96edbeb0-a58d-42eb-8ca1-69698c4e7a96" height="60%" width="60%"
</p>
<br />

<h3>Configuring Help Topics</h3>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/0ddb1aa0-28e2-4188-a8c9-cb013acbb2ac" height="60%" width="60%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring this panel allows users to select topic that can be automatically distributed to departments and given a severity level. I added 4 new ones for this example.
</p>
<p>
<img src="https://github.com/CJones226/post-install-config/assets/158533476/7e699af6-a62c-407d-bdd4-dfda01a334bd" height="60%" width="60%"
</p>
<br />
