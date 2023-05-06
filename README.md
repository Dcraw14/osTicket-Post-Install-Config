@@ -4,27 +4,28 @@
<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />
<h2>Environments and Technologies Used</h2>
- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)
<h2>Operating Systems Used </h2>
- Windows 10 Pro </b> (21H2)
<h2>Post-Install Configuration Objectives</h2>
- Login to the osTicket Admin Panel
- Congfire Roles
- Configure Deparments
- Configure Teams
 - Configure Help Topics

 <h2>Configuration Steps</h2>
 <p> Login to the osTicket Admin Panel. Below displays the tickets for admin/helpdesk User Interface (UI) that will reflect the tickets that are created by the End User ([http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php))
 <p> Login to the osTicket Admin Panel. Below displays the tickets for admin/helpdesk User Interface (UI) that will reflect the tickets that are created by the End User http://localhost/osTicket/scp/login.php

 </p>
 <p align="center">
 <img src="https://i.imgur.com/uzAA73f.png" height="65%" width="65%" alt="UI admin/help desk Tickets"/>
</p>
<br />
- <b>Configure</b> <a href="https://docs.osticket.com/en/latest/Admin/Agents/Roles.html">[Roles]</a> <br /> Roles are the permissions granted to Agents per Department that they have access to. Each Role has a set of permissions that can be checked/unchecked for agents given that Role in association with a Department they have access to. An unlimited number of roles can be created and assigned to Agents with access to various departments.
    <ol>
  <li>Admin Panel -> Agents -> Roles</li>
  <li>Supreme Admin</li>
    </ol>
<p align="center">
<img src="https://i.imgur.com/Jw4EbMN.png" height="65%" width="65%" alt="UI to add Role"/>
</p>
<p>Below we have entered <b>"Supreme Admin"</b> as the role</p>
<p align="center">
<img src="https://i.imgur.com/sJukhDR.png" height="65%" width="65%" alt="enter role name"/>
</p>
<br />
<p> Now we can enable the <a href="https://docs.osticket.com/en/latest/Features/Visibility%20Permissions.html">permissions</a> for this role and as the "Supreme Admin" we've enabled every possible permission available.  
<p align="center">
<img src="https://i.imgur.com/OgnLk0E.png" height="65%" width="65%" alt="list of permissions"/>
</p>
