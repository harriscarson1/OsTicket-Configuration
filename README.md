<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>


<p>
First we need to Remote Desktop into the VM created in the osTicket Setup & Installation section
</p>
<p>
<img src="https://github.com/user-attachments/assets/6220af01-12b8-41ab-be0b-c7267969276b" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Then go to http://localhost/osTicket/scp/login.php to login as an admin
</p>
<p>
<img src="https://github.com/user-attachments/assets/03ee6965-61b2-41d5-91f5-81dcb52c4ef4" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Now we are setting up roles, first click the admin panel button in the top right

</p>
<p>
<img src="https://github.com/user-attachments/assets/c71e2b07-54d3-463f-a853-e702e669f262" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Then go into the agents tab and the roles sub tab, This is where we can view roles and their permissions.
</p>
<p>
<img src="https://github.com/user-attachments/assets/f5474594-f75f-49ca-96c0-76952a5dd099" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
We can add new roles and give those roles the permissions we choose
</p>
<p>
<img src="https://github.com/user-attachments/assets/dce567c6-28bd-4d56-a2f7-afa7b90212d3" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we can look at the departments tab, this is where different departments within the organization can be assigned tickets that pertain to them
</p>
<p>
<img src="https://github.com/user-attachments/assets/239b9a50-9b00-47c8-b2ec-6b5fae2d20b9" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we can make a new department called SysAdmins

</p>
<p>
<img src="https://github.com/user-attachments/assets/579af4e4-6e58-4700-8053-4a74d0912748" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we can go into the teams tab where we can add specific teams who would be able to work on specific tickets.
</p>
<p>
<img src="https://github.com/user-attachments/assets/0b9ef199-b5e5-4a2a-b3a9-d57b8963ae70" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
We can for example add an online banking team  by adding a new team by using the add new team button
</p>
<p>
<img src="https://github.com/user-attachments/assets/11ff7592-d693-4c0b-b29d-e267ef7413f7" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we need to allow anyone to make tickets and not just permitted users so we will go to settings tab in the admin panel then the users sub tab and make sure the registration required tab is UNCHECKED
</p>
<p>
<img src="https://github.com/user-attachments/assets/884a25de-b356-45f4-912d-9890222512d4" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we can go into the agents tab to add a new agent
</p>
<p>
<img src="https://github.com/user-attachments/assets/027dd40a-cbec-4fe5-a2a9-c925725de7b6" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
I will first make jane doe who will be an admin a part of the SysAdmin team and in the online banking department, we also have to put a username and password do that then press create
</p>
<p>
<img src="https://github.com/user-attachments/assets/f0bd21ea-eaf9-4510-85ee-aa890b05ea4c" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
I then made another Agent named John in the support department with read only privilege.

</p>
<p>
<img src="https://github.com/user-attachments/assets/0e8f7e8a-5211-491e-b11e-c73fdba7cbab" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next go back to the agent panel, and then click on the users tab and we can add a user with the Add User button, this is for people that will be creating tickets
</p>
<p>
<img src="https://github.com/user-attachments/assets/51de5615-15ab-49bf-ab32-6353b1ee8afa" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Now we will configure SLAs, so first we need to go back to the admin panel and click on the manage tab then the SLA sub tab
</p>
<p>
<img src="https://github.com/user-attachments/assets/d5c91140-962b-4b99-9036-76e5c75c73f8" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Now i will make 3 SLAs, Sev-A, Sev-B, and Sev-C 
</p>
<p>
<img src="https://github.com/user-attachments/assets/3018e29a-fd72-4fc8-8dbd-c881ba2d18f9" height="80%" width="80%" alt=""/>
  <img src="https://github.com/user-attachments/assets/e756a36c-ac0f-4279-bae2-4cdb9f24b529" height="80%" width="80%" alt=""/>
</p>
<br />

<p>
Next we are going to configure topics which help to further categorize tickets into sections, first we can go to the manage tab and the help topics sub tab, i added a few topics using the Add New Help Topic button.
</p>
<p>
<img src="https://github.com/user-attachments/assets/d33e2695-1f42-441c-acaf-4a0060dc0751" height="80%" width="80%" alt=""/>
<img src="https://github.com/user-attachments/assets/6c3e7823-37fb-4dbb-a054-d13c82b10ece" height="80%" width="80%" alt=""/>
</p>
<br />


In the next section [osTicket Ticket Lifecycle Examples](https://github.com/harriscarson1/OsTicket-Ticket-Lifecycle) we will dive deeper into how these things work in real world examples


