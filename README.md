<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Configuration Steps</h2>

So we've installed osTicket and now we're going to do some post-installation setup. First, we're going to create a new role. On the admin panel, go to Agents->Roles-> add new role. For this role, check all the permissions. Next, add a department and name it "System Administrators".
<p>
<img src="https://imgur.com/DnKOZL6.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://imgur.com/0aObyvI.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<br />

Next, configure "Teams" and add a new one. Go to Agents-> Teams. After, we want to allow anyone to create tickets. To do this, on the Admin Panel go to Settings-> Users. Make sure "Require registration and login to create tickets" is unchecked.
<p>
<img src="https://imgur.com/cpCGfB3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<img src="https://imgur.com/J3gJSF7.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
</p>
<br />

Great, now lets create some agents. These would be employees in an organization. After that, we're going to add users. Go to Agent Panel-> Users -> Add New. We can make up any name we want.
<p>
<img src="https://imgur.com/TVY2jXp.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Alright, now lets configure SLA. SLA plans, or Service Level Agreement, provide a length of time in which help desk admins expect tickets to be closed. To configure go to Admin Panel -> Manage -> SLA -> Add New SLA. Create 3 new SLA plans.
<p>
<img src="https://imgur.com/GraKO81.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />

Lastly, configure help topics by going to Admin Panel -> Manage -> Help Topics. Add the following: Business Critical Outage, Personal Computer Issues, Equipment Request, and Password Reset. These help users categorize their tickets.
<p>
<img src="https://imgur.com/eVmoTxq.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
</p>
<br />
