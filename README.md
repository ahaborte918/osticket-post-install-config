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
- Add Agents under the Admin Panel (e.g., Kim Possible in SysAdmins, Ron Stoppable in Support) and create Users under the Agent Panel (e.g., Karen).
- Set up SLA plans and define Help Topics to organize ticket types and response expectations based on issue severity.

<h2>Configuration Steps</h2>

</p>
After installing osTicket, administrators and support agents log in through the Admin Panel at http://localhost/osTicket/scp/login.php, which provides access to system settings and ticket management tools. This is where agents can configure roles, departments, SLAs, and respond to incoming tickets. End users, on the other hand, submit and track their support requests through the client portal at http://localhost/osTicket.
</p>
[THIS IS THE ADMIN PAGE]
<img width="1797" height="868" alt="osTicket Config 1" src="https://github.com/user-attachments/assets/19a06f5a-4970-4be6-9f9d-26260a30b469" />
</p>
[THIS IS THE AGENT PAGE]
<img width="1866" height="847" alt="osTicket Config 2" src="https://github.com/user-attachments/assets/8ec1f3c9-a6c4-43b9-9a2c-a04dc87d9477" />
</p>
<br />
In the Admin Panel, go to Agents > Roles to create roles like “Supreme Admin” that define what actions agents can perform. Next, navigate to Agents > Departments to organize agents into groups such as “SysAdmins” or “Support,” which control ticket visibility. Then, under Agents > Teams, create teams like “Online Banking” by combining agents from different departments to collaborate on specific types of issues.
</p>
<img width="1135" height="674" alt="osTicket Config 3" src="https://github.com/user-attachments/assets/df820920-7f57-46ce-ae95-ff77401f0bcf" />
<img width="572" height="206" alt="osTicket Config 4" src="https://github.com/user-attachments/assets/7e1cd340-bf3d-40d4-a7a0-0e5f9e0462d7" />
<img width="1142" height="770" alt="osTicket Config 5" src="https://github.com/user-attachments/assets/74cc920d-4703-4019-bb31-94e1cb03db82" />
</p>
<br />
To control who can submit support tickets, go to the Admin Panel, then Settings > User Settings. Uncheck the box that allows unregistered users to create tickets, which ensures that only registered users can submit requests. This helps maintain a more secure and manageable ticketing system by requiring user authentication.
</p>
<img width="572" height="400" alt="osTicket Config 6" src="https://github.com/user-attachments/assets/ffdc1658-30c6-463c-a540-e19697bce8ef" />
</p>
<br />
In the Admin Panel, go to Agents > Add New to create agent accounts like Kim (assigned to SysAdmins) and Ron (assigned to Support). Agents are staff members who manage and respond to tickets. To add end users (customers), switch to the Agent Panel, go to Users > Add New, and create profiles for users like Karen and Ken who will submit support requests.
</p>
<img width="1139" height="746" alt="osTicket Config 7" src="https://github.com/user-attachments/assets/7cba316c-5d22-4ffa-8947-908cbe3d57a3" />
<img width="1145" height="347" alt="osTicket Config 8" src="https://github.com/user-attachments/assets/51a988e1-1677-4cde-b39b-befc049e1a2b" />
</p>
<br />
In the Admin Panel, navigate to Manage > SLA to create Service Level Agreements such as Sev-A, Sev-B, and Sev-C, each with different response time expectations and schedules. These SLAs help prioritize tickets based on urgency and ensure timely support. 
</p>
<img width="954" height="459" alt="osTicket Config 9" src="https://github.com/user-attachments/assets/34dd98d5-f83a-40dd-96a0-5f7e376b7774" />
<img width="1136" height="480" alt="osTicket Config 10" src="https://github.com/user-attachments/assets/91d37850-230d-4880-b8e2-cd21a0b354c3" />
<img width="1149" height="468" alt="osTicket Config 11" src="https://github.com/user-attachments/assets/3067b222-c497-480e-8994-748f8acdbc50" />
<img width="571" height="223" alt="osTicket Config 12" src="https://github.com/user-attachments/assets/c1d64370-60b6-4260-90ea-c3f02db2dde6" />
</p>
<br />
Then go to Manage > Help Topics to create categories like Password Reset or Business Critical Outage, which users select when submitting tickets to streamline routing and handling.
</p>
<img width="1113" height="474" alt="osTicket Config 13" src="https://github.com/user-attachments/assets/90586cad-d9bd-47d3-8747-c9277a2d16e1" />
<img width="1069" height="460" alt="osTicket Config 14" src="https://github.com/user-attachments/assets/655bc722-16ab-4f3e-b25f-abe5e1600fd9" />
<img width="620" height="385" alt="osTicket Config 15" src="https://github.com/user-attachments/assets/6963a541-1c96-4080-a44d-234f52dea4c2" />
</p>
<h2>Final Thoughts</h2>
