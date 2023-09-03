# OsTicketPreReqs
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- 1:Create A Windows 10 VM with 4VCPUs Using Microsoft Azure.
- 2:download PHP manager and other setup installations like(VC.Redist, Rewrite.RMD).
- 3:Setup My SQL and osticket systems to start your own ticketing system
- 4:enable extensions through PHP Manager and create a new session and sql with heidi SQL.
- 5:setup permissions withing the osticket folders and creat new osticket domain.

<h2>Installation Steps</h2>


<img src="blob:chrome-untrusted://media-app/f46899aa-cb6c-439f-b635-f4f6c8825cbe" alt="Screenshot 2023-09-03 11.39.22 AM.png"/>![image](https://github.com/SDhinton1/OsTicketPre/assets/143854836/8673b26f-2323-449b-ad10-b4fec7ea4ab2)

Log into Microsoft azure and create a resource group labeled Osticket(or whatever you choose) Then make a VM from the Virtual Machine page and proceed to make a VM(Windows 10, 4VCPUs and 16GB of Gib of memory copy ip address and paste to Remote Desktop.
</p>
<br />

<p>
<img src="blob:chrome-untrusted://media-app/654fca6d-6940-4018-b9c5-3556e950b543" alt="SGhqd31 - Imgur.png"/>![image](https://github.com/SDhinton1/OsTicketPre/assets/143854836/6f73983f-15de-491f-a6af-0d3f58123be8)

When working through IIS download the os ticket extension and enable php extensions configure permissions in the ost file, download heidiSQL and make the SQL for the osticket website.
</p>
<br />

<p>
<img src="blob:chrome-untrusted://media-app/bde0858a-d1eb-4195-a403-968b8eed2ba2" alt="Screenshot 2023-09-03 1.11.34 PM.png"/>![image](https://github.com/SDhinton1/OsTicketPre/assets/143854836/b7320ff6-5959-4f2e-9e37-fd3c13c3e2ba)
</p>
<p>
After logging in with your root name and password through heidiSQL your new osticket website has now opened up so you can now open tickets, create users, and run your own ticketing system.
</p>
<br />
