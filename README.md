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

- Configure Roles
- Configure Departments
- Configure Teams
- Configure Agents (workers)
- Configure Users (customers)
- Configure SLA
- Configure Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/2cd7e2d8-59e3-43df-b5d2-668b55220423" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Roles -
Admin Panel -> Agents -> Roles.
Create a Supreme Admin role

</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/1d1b55b7-50ee-4939-b2bf-783ecc11afbc" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Departments -
Admin Panel -> Agents -> Departments
create a System Administrators role
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/700be0f0-a1eb-40ea-9094-026e22cfce51" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Teams
Admin Panel -> Agents -> Teams
create a Level I Support team and
Level II Support team
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/bfaddf81-b0b3-478a-a5b6-173c6ee1f013" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Agents (workers)
Admin Panel -> Agents -> Add New Agents
Jane and
John. Set Jane's access to Supreme Admin. Set Jane's team as Level II Support. Set John's access to Supreme Admin. Set John's team as Level II Support.
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/dba4694c-1ba7-4c01-9e07-d4b9cdb17f78" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Users (customers)
Agent Panel -> Users -> Add New Users
Karen and
Ken. 
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/d4b45175-1da0-4958-bd5d-a96c1c63d84b" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure SLA
Admin Panel -> Manage -> SLA. Create 3 SLA's
Sev-A (1 hour, 24/7)
Sev-B (4 hours, 24/7)
Sev-C (8 hours, business hours)
</p>
<br />

<p>
<img src="https://github.com/seanmaldonadooo/post-install-config/assets/149026184/c24635d0-78ec-419b-b92a-cc70edb3eec4" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configure Help Topics
Admin Panel -> Manage -> Help Topics.
Business Critical Outage,
Personal Computer Issues,
Equipment Request,
and Password Reset
</p>
<br />
