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

- Assigning an Administrator account
- Assigning Employee accounts
- Congigure User accounts
- Configure SLA
- Configuring Help Topics

<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/GatHR0A.png" Height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Log into //localhost/osTicket/scp/login.php. Click on Admin Panel secondly click agents then click on Roles. At this poimt create a new role such as  Supreme Administrator. Finally set permissions.
</p>
<br />
<p> 
 <img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>  
</p>  
 <p>
Configure Departments click Admin Panel --> Agents --> Departments. Create a System Administrator Department
  </p>
  <br />
  
  <img src="https://i.imgur.com/qxd49Xn.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
  </p>
  <p>
   Configure Teams click Admin Panel --> Agents -->Teams. Teams can be created such as different levels of Supports would have access to different Applications.
  </p>
  <br />
  
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
 Permission to create tickets click Admin Panel --> Settings --> User Settings. Then go to Registration Required and the decision can be made about registration and login to create tickets.
 </p>
 <br />
 
 <img src="https://i.imgur.com/YxECXJW.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
</p>
<p>
 Configure Agents click Admin Panel --> Settings --> User
</p>
<br />

  <img src="https://i.imgur.com/cWeNIAw.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring Users this time click Agent Panel next Users then click Add New. These agents will be the end users they will be putting tickets in from http://localhost/osTicket.
</p>
<br />

<img src="https://i.imgur.com/zBhN6lj.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p> 
<p>
Configuring SLA click on Admin Panel --> Manage -->SLA. Then create your levels of SLA that consist of resoponse time along with the time span for an example there must be a response within 1 hour of the ticket 24/7 is its a Sev-A.
</p>
<br />

<p>
<img src="https://i.imgur.com/xnHiuYr.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Configuring the Help Topic click in this order Admin Panel, Manage, and Help Topic. From there stay with the ones that are default or create new ones. 
</p>
<br />
