<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
In this project we will focus on the post-installation configuration of osTicket, including setting up roles, departments, help topics, and user permissions to optimize workflow management. It demonstrates how to customize the ticketing system for efficient IT support and customer service operations.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 11</b> (24H2)

<h2>Post-Install Configuration Objectives</h2>
- STEP 1 - Log into the Admin Panel via http://localhost/osTicket/scp/login.php and direct users to the client portal at http://localhost/osTicket.
- STEP 2 - In the Admin Panel, configure Roles, Departments, and Teams to manage agent permissions, visibility, and cross-department collaboration.
- STEP 3 - Adjust User Settings to require registration before users can create tickets by unchecking the "unregistered users" option.
- STEP 4 - Add Agents under the Admin Panel (e.g., Kim Possible in SysAdmins, Ron Stoppable in Support) and create Users under the Agent Panel (e.g., Karen).
- STEP 5 - Set up SLA plans and define Help Topics to organize ticket types and response expectations based on issue severity.

<h2>Configuration Steps</h2>

</p>
After installing osTicket, administrators and support agents log in through the Admin Panel at http://localhost/osTicket/scp/login.php, which provides access to system settings and ticket management tools. This is where agents can configure roles, departments, SLAs, and respond to incoming tickets. End users, on the other hand, submit and track their support requests through the client portal at http://localhost/osTicket.
</p>
[THIS IS THE ADMIN PAGE]
<img width="1797" height="868" alt="osTicket Config 1" src="https://github.com/user-attachments/assets/19a06f5a-4970-4be6-9f9d-26260a30b469" />
</p>
[THIS IS THE AGENT PAGE]
<img width="1143" height="402" alt="osTicket Config 2" src="https://github.com/user-attachments/assets/8e14809a-4f6b-46ea-98b1-76ef60429fcf" />
</p>
<br />
In the Admin Panel, go to Agents > Roles to create roles like “Supreme Admin” that define what actions agents can perform. Next, navigate to Agents > Departments to organize agents into groups such as “SysAdmins” or “Support,” which control ticket visibility. Then, under Agents > Teams, create teams like “Online Banking” by combining agents from different departments to collaborate on specific types of issues.
</p>
<img width="1135" height="575" alt="osTicket Config 3" src="https://github.com/user-attachments/assets/fe5f06e3-b3b8-443a-8e8e-ce30ec4328a2" />
<img width="572" height="178" alt="osTicket Config 4" src="https://github.com/user-attachments/assets/cef18504-e180-450b-82f9-5fd19ae6c773" />
<img width="1129" height="715" alt="osTicket Config 5" src="https://github.com/user-attachments/assets/14091a96-f688-42af-9817-ed6c39283251" />
</p>
<br />
To control who can submit support tickets, go to the Admin Panel, then Settings > User Settings. Uncheck the box that allows unregistered users to create tickets, which ensures that only registered users can submit requests. This helps maintain a more secure and manageable ticketing system by requiring user authentication.
</p>
<img width="572" height="360" alt="osTicket Config 6" src="https://github.com/user-attachments/assets/1ea55e59-d997-4ba3-8986-900101d9248a" />
</p>
<br />
In the Admin Panel, go to Agents > Add New to create agent accounts like Kim (assigned to SysAdmins) and Ron (not pictured below, but was assigned to Support in osTicket). Agents are staff members who manage and respond to tickets. To add end users (customers), switch to the Agent Panel, go to Users > Add New, and create profiles for users like Karen and Ken who will submit support requests.
</p>
<img width="1139" height="746" alt="osTicket Config 7" src="https://github.com/user-attachments/assets/054882e5-057f-4cc9-8cb9-e583c4fc0feb" />
<img width="1145" height="347" alt="osTicket Config 8" src="https://github.com/user-attachments/assets/0e4de517-13f5-4529-adde-9cb05dea0dc2" />
</p>
<br />
In the Admin Panel, navigate to Manage > SLA to create Service Level Agreements such as Sev-A, Sev-B, and Sev-C, each with different response time expectations and schedules. These SLAs help prioritize tickets based on urgency and ensure timely support. 
</p>
<img width="954" height="434" alt="osTicket Config 9" src="https://github.com/user-attachments/assets/825ef413-7f8e-462f-b4d7-9d7001dcf107" />
<img width="1136" height="480" alt="osTicket Config 10" src="https://github.com/user-attachments/assets/c433e135-acc1-498d-92a7-7d124e1e07cb" />
<img width="1149" height="468" alt="osTicket Config 11" src="https://github.com/user-attachments/assets/febc346f-7736-4687-9f11-e8049f443386" />
<img width="571" height="193" alt="osTicket Config 12" src="https://github.com/user-attachments/assets/59e1049f-877b-49e8-98aa-d55cc186ecd0" />
</p>
<br />
Once we are finish with the SLAs, head to Manage > Help Topics to create help topic categories like Password Reset or Business Critical Outage, which users select when submitting tickets to streamline routing and handling.
</p>
<img width="1113" height="426" alt="osTicket Config 13" src="https://github.com/user-attachments/assets/f7e56828-1570-4db5-a725-102dd6b752fb" />
<img width="1069" height="430" alt="osTicket Config 14" src="https://github.com/user-attachments/assets/5322bbf1-5e9b-4bcf-b7f9-fd54705880ee" />
<img width="620" height="385" alt="osTicket Config 15" src="https://github.com/user-attachments/assets/6963a541-1c96-4080-a44d-234f52dea4c2" />
</p>

<h2>Final Thoughts</h2>
This project enhanced my understanding of customizing osTicket beyond installation by configuring roles, departments, and workflows to streamline support operations. It reinforced the value of tailoring help desk systems to meet organizational needs for efficiency and scalability.
