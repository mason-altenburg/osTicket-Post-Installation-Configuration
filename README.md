<img width="700" height="200" alt="image" src="https://github.com/user-attachments/assets/c0201915-4b89-48b6-a6d3-4abecf2d563b" />

# osTicket-Post-Installation-Configuration
This tutorial demonstrates the post configuration setup of the osTicket system .

Okay wonderful! We have successfully configured osTicket from scratch. Now we will do some system administration and work on some post installation setup. first we will configure new roles within the help desk. In order to do so go to Admin panel-> Agents-> Roles. We will create a Supreme Admin. Click on "Add new role" then enter the name of the new role. You can also modify any specific roles permissions. In this case since we are creating a Supreme Admin they will be given all permissions. Keep in mind roles are used to determine an agents permissions so not all agents will have unlimited access. If you followed the steps correctly your screen should like something like this. As you can see we have successfully created the "Supreme Admin" role.

<img width="1262" height="431" alt="image" src="https://github.com/user-attachments/assets/b1f4e80c-4e36-4f33-b99f-b2d4a214a9b7" />
 
 Select the "Departments" button in the agents tab. Here we will be able to create a new department. Each Agent is assigned to a specific department depending on their assigned role within the helpdesk. In this case we will be creating the "System Administrators" department, this is where the Supreme Admins will be designated. Other specific settings such as SLAs, managers and other email settings can be set up in the departments tab.
 
 <img width="1053" height="854" alt="image" src="https://github.com/user-attachments/assets/81309c4d-2d32-4022-9b78-782bf7005c4f" />

After configuring a new department we will set up a new team. Teams allow you to pull agents from different departments you can have an A team that has top technicians from specific departments. For example you can create a help topic that correlates with a product you produce, and assign it to a team of agents that specialize in that particular product. To set up a team go to Agents->Teams. A Level I support team has been created by default, in this example we will create a Level II Support Team.

<img width="1261" height="781" alt="image" src="https://github.com/user-attachments/assets/a6f28ba6-f08c-488f-bccb-e51ea80829f0" />

Now that we have set up a new team we will create a new setting that will allow anyone to create tickets. Admin Panel->Settings->User Settings.

<img width="1265" height="766" alt="image" src="https://github.com/user-attachments/assets/48c98cd1-f70f-417c-91a3-e7c28e2388e0" />

It is now time to create Agents. Agents are the employees of the helpdesk that actually work on solving tickets. Agents are assigned primary departments and given a primary role for tickets sent to their department. Agents can be given access to other departments other than their own, they can also have different roles depending on which department they are in. Permissions, Access, & Teams are be assigned in the Agents tab.

<img width="952" height="832" alt="image" src="https://github.com/user-attachments/assets/7ed93b06-2933-4eaa-8f7d-aa4428a31e40" />

After creating some agents we will create users. Users are customers that create tickets when they are having issues. A user is identified with their E-mail address. To create a user follow this path Agent Panel->Users->User Directory->Add new.

<img width="1236" height="417" alt="image" src="https://github.com/user-attachments/assets/08a0740e-f4d7-4b3f-90ab-f7c4e559b428" />

SLAs Plans provide a length of time in which the help desk is expected to take in order to solve a specific ticket. SLA Plans are created by going to Admin Panel->Manage->SLA Plans. Each SLA has a schedule and within that schedule there is a grace period. In this example SEV-A has a 24/7 and a one hour grace period.

<img width="1227" height="740" alt="image" src="https://github.com/user-attachments/assets/d9852bf3-35db-4bd0-a3bc-e54a754c82eb" />

Help topics help users categorize their tickets. In the example below we have made a help topic for "Business Critical Outage" this can be if customers cannot access mobile banking.

<img width="1212" height="702" alt="image" src="https://github.com/user-attachments/assets/cc77943c-b93a-4d42-b099-008667e9dd27" />
