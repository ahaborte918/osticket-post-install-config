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

- Windows 11</b> (24H2)

- <h2>Post-Install Configuration Objectives</h2>

- Log into the Admin Panel via http://localhost/osTicket/scp/login.php and direct users to the client portal at http://localhost/osTicket.
- In the Admin Panel, configure Roles, Departments, and Teams to manage agent permissions, visibility, and cross-department collaboration.
- Adjust User Settings to require registration before users can create tickets by unchecking the "unregistered users" option.
- Add Agents under the Admin Panel (e.g., Spongebob in SysAdmins, Patrick in Support) and create Users under the Agent Panel (e.g., Eugene Krabs).
- Set up SLA plans and define Help Topics to organize ticket types and response expectations based on issue severity.

<h2>Configuration Steps</h2>

</p>
After installing osTicket, administrators and support agents log in through the Admin Panel at http://localhost/osTicket/scp/login.php, which provides access to system settings and ticket management tools. This is where agents can configure roles, departments, SLAs, and respond to incoming tickets. End users, on the other hand, submit and track their support requests through the client portal at http://localhost/osTicket.
</p>
<br />
<img

<img
