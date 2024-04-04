<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Post-Install Configuration</h1>

This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />

[osTicket: Prerequisites and Installation](https://github.com/sirmichaelyoung/osticket-prereqs) Continued


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Post-Install Configuration Objectives</h2>

- Configure the Following
  - Roles
  - Departments
  - Teams
  - Agents (staff)
  - Users (customers)
  - Service-level agreement (SLA)
  - Help Topics
- Enable Ticket Creation for Anyone

<h2>Configuration Steps</h2>

<img width="581" alt="Screenshot 2024-04-04 at 12 40 15 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/579d129e-5177-405d-999d-c4fe0b58a29d">

Roles:
- Admin Panel > Agents > Roles
  - Add New Role (example)
    - Chief Admin 
      - Enable all permissions (Tickets, Tasks, Knowledgebase)

<img width="630" alt="Screenshot 2024-04-04 at 12 49 36 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/2b0722ab-2dd4-4b07-87d5-ab3293055151">

Departments:
- Admin Panel > Agents > Departments
  - Add New Department (example)
    - System Administrators 
 
<img width="566" alt="Screenshot 2024-04-04 at 12 52 30 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/8c92062e-a1b8-4ab8-b333-3636e7f3e95f">

Teams:
- Admin Panel > Agents > Teams
  - Create New Teams (example)
    - Level I Support
    - Level II Support

<img width="561" alt="Screenshot 2024-04-04 at 12 58 28 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/cb7b8d1b-134f-4cd6-8a85-a411aa87dd52">

Agents (staff):
- Admin Panel > Agents > Agents
  -  Add New Agent (example)
    - Jazmine 
      - Add Username/Set Password
      - Define Access and Permissions

<img width="549" alt="Screenshot 2024-04-04 at 1 09 20 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/ae3047a4-c5e0-4fb2-8fd5-7595d9c1d0f3">

Users (customers)
- Agent Panel > Users > User Directory
  - Add User (example)
   - Jacob

<img width="565" alt="Screenshot 2024-04-04 at 1 21 10 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/3e7cdf20-64ca-460b-9ec8-175955fe564a">

Service-level agreement (SLA):
- Admin Panel > Manage > SLA
  - Add New SLA Plan (example)
   - Sev-A (1hr, 24/7)
   - Sev-B (4hr, 24/7)
   - Sev-C (8hr, Monday-Friday)

  <img width="568" alt="Screenshot 2024-04-04 at 1 27 19 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/6113e972-6604-42f0-bde1-f1b8fed67fd2">

Help Topics:
- Admin Panel > Manage > Help Topics
  - Add New Help Topic (example)
    - Business Critical
    - Personal Critical
    - Hardware Request
    - Password Reset
   
  <img width="344" alt="Screenshot 2024-04-04 at 1 33 45 AM" src="https://github.com/sirmichaelyoung/post-install-config/assets/163785883/b8c1e43c-9ccd-4d10-b294-dabbdca1f31d">

Enable Ticket Creation for Anyone:
- Admin Panel > Settings > User Settings
  - Ensure "Registration Required" is not selected.
  - Ensure "Registration Method" is set to "Public"
 
This concludes the Post-Install Configuration.

Continue [osTicket: Ticket Lifecycle Examples](https://github.com/sirmichaelyoung/ticket-lifecycle)
