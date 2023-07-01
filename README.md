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

<h2>Roles</h2>
Our first step will be to configure various Roles, Departments, and Teams. To begin, look at the top right of the interface and select Admin Panel -> Agents -> Roles. From this step we shall add a new role and name it "Supreme Administrator," and check all available boxes for this role's creation.
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/9876671e-a245-4fc4-b335-431601ed23aa"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/877551b1-78b6-4233-a629-3a965fe0999c"/>
</p>
</p>
<h2>Departments</h2>
Next select Departments -> Add a New Department. Name the Department "System Administrators" and click create dept. 
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/e8bb353e-9acf-48ea-aaa8-b989abf55230"/>
</p>
<h2>Teams.</h2>
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
</p>
To allow anybody to create tickets, you must select Admin Panel -> Settings -> User Settings to get to the menu shown above. Ensure that the registration required box is not selected as shown above.
</p>
<h2>Configuring Agents (Employees)</h2>
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/1d874011-d737-435e-8d64-8d2925ea3160"/>
</p>
</p>
On this next step we will be adding some new agents to operate tickets. To add a new agent select, Admin Panel -> Agents -> Add New.
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/1f5922e7-26a8-4895-ad15-e9d382c59d28"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/684a938d-9029-4e82-b46e-afb43265f988"/>
</p>
</p>
Be sure to set a username and set a password for your agents as shown above. Also be sure to enter the Access and Teams tab, and assign your agent's a Deptartment, Team, and access levels.
</p>
</p>
<h2>Configuring Users (Customers)</h2>
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/4beeae02-23c0-4233-9a33-5f521e2aebaf"/>
</p>
</p>
To set up Users we are going to enter by selecting Agent Panel -> Users -> Add New. In this example below you can see I have added Karen and Ken, as users.
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/05e22a63-0cb9-4705-87f9-b78909cb98e6"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/555e62a4-189e-4780-a1c3-b275f447177d"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/a89ea96a-73a6-4cb6-91c3-46704b20f3b7"/>
</p>
</p>
<h2>Configuring SLA</h2>
In this step we are going to set up a few different Service Level Agreements with various priority levels. You can reach the necessary page by 
selecting Admin Panel -> Manage -> SLA.
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/8e275ae8-315e-4c4c-8d82-c499f0b70cbd"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/c9393594-a6d4-4b23-9149-eee5e4259dda"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/3eea85bc-d384-42d7-b383-e344ed7851b8"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/1583d357-ecb2-4b1d-a77d-58342ce01ff4"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/35c86cc0-e9fb-4aaf-a4e3-6f35eb4c4a33"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/a8f4a289-cf0e-4434-bcc7-4b995500593d"/>
</p>
</p>
As you can see above, there are a few SLA's with various levels of priority now established.
</p>
</p>
<h2>Configure Help Topics</h2>
Lastly, we are going to configure some common help topics for our system. You can also reach this page 
by selecting Admin Panel -> Manage -> Help Topics
</p>
</p>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/60073db5-e32a-449a-9e4c-85aca8f83ebf"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/b05726e5-2182-45c0-9962-bcf942fab340"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/4f99dc19-286f-4725-bd85-870b633295fc"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/19610ebb-dde6-4748-9969-26fec1e46cc3"/>
<img src="https://github.com/ashtvanf/osTicket-post-install-config/assets/138221709/6a3f8bbb-e919-4adc-9552-d4ac13d583bf"/>
</p>
</p>
As shown above, I have set up some various help topics. 
</p>
</p>
