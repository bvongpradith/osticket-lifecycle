<p align="center">
<img src="https://www.synaxiom.com/wp-content/uploads/2016/06/osticket.png" alt="osTicket logo"/>
</p>

<h1>osTicket Lifecycle</h1>
In this tutorial, we will be going over the lifecycle of a ticket from creation to closing in osTicket. This tutorial has prerequisites that must be completed before continuing which will be linked below. </p>

- [osTicket: Prerequisites and Installation](https://github.com/bvongpradith/osticket-prereqs)
- [osTicket: Post-Installation Configuration](https://github.com/bvongpradith/osticket--post)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- Internet Information Services (IIS)
- osTicket
- HeidiSQL

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Steps</h2>

- Ticket Creation
- Assignment and Communication
- Resolving Issue
- Resolution

<h2>Detailed Steps</h2>

<p>
<img src="https://i.imgur.com/JRAbLzQ.png"/>
</p>
<p>
First, in the VM go to http://localhost/osTicket/ and open a new ticket.
</p>
<br />

<p>
<img src="https://i.imgur.com/Ioir8j4.png"/>
</p>
<p>
Next, use either Karen or Ken for the email and full name for the ticket. Choose a help topic and create a fake scenario that a customer might face. For this tutorial, we will be asking for password reset.
</p>
<br />

<p>
<img src="https://i.imgur.com/o92b2CF.png"/>
</p>
<p>
Now go to http://localhost/osTicket/scp/login.php and go to the Agent Panel.
</p>
<br />

<p>
<img src="https://i.imgur.com/lmXHiC8.png"/>
</p>
<p>
Afterwards, navigate to the tickets panel and select the ticket you created. Assign the ticket to either a user or admin and set the SLA plan to SEV-C since it can be done on a weekday when the customer will need to log in. Depending on the severity of the ticket, it will be assigned differently.
</p>
<br />

<p>
<img src="https://i.imgur.com/NPdo5H2.png"/>
</p>
<p>
Finally, you will be able to respond to the ticket and decide if it can be resolved or stay open. 
