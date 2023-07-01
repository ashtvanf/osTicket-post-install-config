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

- Configure Roles, Departments, and Teams.
- Allow anyone to create tickets.
- Configure Agents (Employees), as well as configure Users (Customers).
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps for Roles, Departments, And Teams.</h2>

Our first step will be to configure various Roles, Departments, and Teams. To begin, look at the top right of the interface and select Admin Panel -> Agents -> Roles. From this step we shall add a new role and name it "Supreme Administrator," and check all available boxes for this role's creation.

<p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/9876671e-a245-4fc4-b335-431601ed23aa"/>
</p>

</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/877551b1-78b6-4233-a629-3a965fe0999c"/>
</p>
</p>
Next select Departments -> Add a New Department. Name the Department "System Administrators" and click create dept. 
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/e8bb353e-9acf-48ea-aaa8-b989abf55230"/>
</p>
Now that we have created a Department, we are going to create a new team. At the top of the available menu, 
select Admin Panel -> Agents -> Teams. From here, we are going to create both a Support I and Support II team.
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/6deb2d47-e92a-476e-9d5e-67b1ff78a632"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/68f708c1-ac2a-401e-b977-0e893dce3f0c"/>

</p>
</p>
</p>
<br />
<h2>Allow anybody to create tickets</h2>
<p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/a03291aa-5de4-401e-a153-0d21a1d62c0a"/>
</p>
<p>
To allow anybody to create tickets, you must select Admin Panel -> Settings -> User Settings to get to the menu shown above. Ensure that the registration required box is not selected as shown above.
</p>
<br />
