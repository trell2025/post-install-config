<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://youtu.be/ndulV12wmog)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Email Configuration (Incoming & Outgoing)
- Departments and Agent Assignment
- Automation: Triggers, SLAs, and Routing
- Backup Configuration
- Customer Portal & User Registration

<h2>Configuration Steps</h2>

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_emails_settings_settings.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Outgoing Email (SMTP):

Go to Admin Panel > Settings > Email.
Set up SMTP with your email provider’s details (SMTP server, port, username, password).
Test the configuration to ensure successful email sending for notifications.
Incoming Email (IMAP/POP3):

In Email Settings, configure IMAP/POP3 settings to fetch emails and create tickets automatically.
Set up your mailbox credentials (server, port, username, password).
Test the configuration to verify incoming emails are converted into tickets.
</p>
<br />

<p>
<img src="https://automationedge.com/wp-content/uploads/2023/11/ImportedPhoto.756024847.641124.webp" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Triggers: Automate actions based on ticket conditions. For example, you can set up triggers to automatically assign tickets to specific agents, send email notifications, or update ticket status when certain conditions (like ticket priority or department) are met.

SLAs (Service Level Agreements): Define response and resolution times for different ticket priorities or departments. SLAs ensure that tickets are addressed within a specific timeframe, helping meet customer expectations and improving support efficiency.

Routing: Automatically assign tickets to the correct department or agent based on predefined criteria, such as the help topic or ticket type. This ensures tickets are efficiently directed to the right team for faster resolution.
</p>
<br />

<p>
<img src="https://docs.osticket.com/en/latest/_images/admin_settings_user_userSettings.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
the Customer Portal allows users to submit, track, and manage their support tickets. Customers can view the status of their tickets, update information, and communicate with support agents through the portal.

User Registration enables customers to create accounts, providing access to the portal where they can submit new tickets, check ticket history, and update personal details. Depending on configuration, users can either register and log in or submit tickets as guests without an account.

The portal enhances customer experience by offering self-service options and a central location for ticket management.
</p>
<br />
