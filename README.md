<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial details the post-installation configuration of the-source help desk ticketing system, osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Microsoft Azure
- Windows Virtual Machine
- Remote Desktop
- Internet Information Services (IIS)
- osTicket

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DUtnTz4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
 - Agents and managers can be assigned to one or more departments via the Admin Panel's Agents tab. 
  
- These departments, which can be either private or, are used to route tickets in the help desk system. To configure departments, navigate to the Admin Panel's Agents tab.
<br />

<p>
<img src="https://i.imgur.com/hO1Q5VO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- To enable agents to respond to efficiently and tickets, they granted access to the help desk and can be assigned to various departments. When adding an agent, a primary department can be designated for them, along with a primary role the tickets and tasks routed to that department.
  
- Additionally, agents can be given extended access to other departments within the help desk and assigned different roles for those departments. This allows them to effectively manage a of tasks within the help desk system.
</p>
<br />

<p>
<img src="https://i.imgur.com/HuvBaIB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>

<p>
<img src="https://i.imgur.com/LGLVOU7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Within the Agents tab of the Admin Panel, you have the ability to assign agents and managers various departments. These departments are utilized to route tickets within the help desk system and can be designated either private or public.
  
- Additionally, you can establish roles for each department to which an agent has access. These roles comprise a set of permissions that can be enabled or disabled for the agent within that department.
  
- A number of roles will be created and assigned to agents with access to different departments.
</p>
<br />

<p>
<img src="https://i.imgur.com/Up9l6Wg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- A Service Level Agreement (SLA) is a contract between a service provider and its customers that specifies the expected level of service from the provider. It includes such as the types of services offered, the performance standards for services, and the consequences of failing to meet those standards. 
  
- SLAs are commonly used in the IT industry to ensure that customers receive a certain level of service support from their provider.
  
- To create SLA Plans in the help desk system, go to the Manage tab in the Admin Panel, click the "Add New SLA Plans" button. These plans outline the time frame for closing tickets in the help desk


</p>
<br />
<br />

<h2>osTicket Configurations are Complete </h2>

With the configurations now in place, I can effectively utilize osTicket as a proper ticketing. I am able create tickets and triage them as if were operating in a real environment.
