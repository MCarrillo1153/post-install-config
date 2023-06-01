<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
- PHP
- osTicket (Help Desk Ticketing System

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Configuration Steps</h2>
Configure roles in the admin panel. Admin Panel > Agents > Roles > Add New Role > Type "Supreme Admin" for the name > Add role > Check every box under the permissions tab > Add role. (NOTE: To switch between the admin and agent panel look at the top of the page. If it reads Admin panel it means you are in the agent panel and vice versa.)
</p>
<p>
<img src="https://i.imgur.com/qW13T9X.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/TJSfFGO.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/ThIBP4n.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/a6v9A4D.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/5u70CPs.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/c7SBPVB.png" height="80%" width="80%"/> 
</p> 
</p>
<br />

Configure the departments. Admin Panel > Agents > Departments > Type: System Administrators for department name > Create Dept.
</p>
<p>
<img src="https://i.imgur.com/EOVfPq7.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/4uE6s4j.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/PWPXqjz.png" height="80%" width="80%" />
</p>
<br />

Configure Teams. Admin Panel > Agents > Teams > Add Teams (Create Level II Support) > Add yourself as a memeber of Level II Support > Create Team.
</p>
<p>
<img src="https://i.imgur.com/rmDERXy.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/p3ilQ2Q.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/TQkNIUR.png" height="80%" width="80%"/>
</p>
<p>
<img src="https://i.imgur.com/C9hWdIG.png" height="80%" width="80%"/>
</p>
<br />

Allow anyone to create tickets. Admin Panel > Settings > User Settings. Check the box to Require Registration and login to create tickets > Save Changes.
</p>
<p>
<img src="https://i.imgur.com/7k2G95V.png" height="80%" width="80%"/>
</p>
<br />

Congfigure Agents (For employees that work the tickets). Go to Agents tab > Agents > Add new Agent (NOTE: make sure you are still in the admin panel). 
</p>
<p>
<img src="https://i.imgur.com/aZPNENy.pngL" height="80%" width="80%"/>
</p>
<br />

Give the new agent a random name you'd like, in my instance I will use "Jane Doe". Check the Administrator box > Set Username to whatever you like > Set Password > Uncheck "Send the agent a password reset email" then uncheck require password change at next login > Set any password you like > Set
</p>
<p>
<img src="https://i.imgur.com/9T3bAkd.png" height="80%" width="80%"/>
</p>
<br />

Set the department for the agent in the Access tab > Under Permissions check all the boxes > Under Teams tab add Level I support.
</p>
<p>
<img src="https://i.imgur.com/1ppSvQ5.png" height="80%" width="80%"/>
</p>
<br />

Give the new agent a random name you'd like, in my instance I will use "Jane Doe". Check the Administrator box > Set Username to whatever you like > Set Password > Uncheck "Send the agent a password reset email" then uncheck require password change at next login > Set any password you like > Set
</p>
<p>
<img src="https://i.imgur.com/9T3bAkd.png" height="80%" width="80%"/>
</p>
<br />
