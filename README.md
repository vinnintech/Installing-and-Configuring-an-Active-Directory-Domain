
<p align="center">
<img width="272" height="185" alt="image" src="https://github.com/user-attachments/assets/3598555c-e728-4e21-820d-1b5ac9981fa5" />

 
  # Installing and Configuring an Active Directory Domain
  
  

## Description
This project demonstrates how to set up a domain in Active Directory using Server Manager. It covers installing Active Directory Domain Server and promoting the server to a domain controller.
## Utiliities & Enviroments Used
- Server Manager
- Windows Sever 2025
- Windows 11
## Project Walkthrough:
Once we have installed Windows Server, Server Manager will be what will open in the Server. In order to not get confused during the lab, we will rename the computer.

1. Click Local Server on the left hand side.
2. Select the blue highlighted computer name.
3. Click change in the System Properties to ranme computer.
4. Change it to a name that you desire (In this instance, I named it Server2025).
5. The comptur will restart once you change it.

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/f6a5f956-6939-4be1-864d-55ebe8ce7ae0" />
<img width="1326" height="743" alt="image" src="https://github.com/user-attachments/assets/b1c23024-4454-47bc-8a86-06faade54cc8" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/54edb8ec-f824-48e3-9a41-e615038dc150" />

## Installing Active Directory
1. Click Manage and "Add roles and features".
3. For installation type click "Role-based"
4. Click Active Directory Domain Services and Add Features.
5. Install

<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/971396a9-bd72-4e5a-be0b-6ce9af0bf1cf" />
<img width="975" height="528" alt="image" src="https://github.com/user-attachments/assets/ad835ce4-ef1d-4947-9061-2dd1906f93ab" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/7b7a933d-f249-40db-b8e0-4ea4a469f310" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/3f8e385f-3ab1-4d79-996e-a55d0e532746" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/9f8fc8d5-19bf-4c06-b305-791e5f6b36a5" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/8b6800a2-75fb-45f4-92d8-dc28385dcd5a" />


##  Promote Server to Domain Controller
1. On the same installation page that is completed, select "Promote this server to a domain controller.
2. Click Add a new forest and name your domain. (For this instance, I will use vinnintech.com).
3. Create password and proceed.
4. BIOS name will auto populate, but you can name it whatever you like.
5. Proceed and install
 - Computer will restart once completed.

<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/aa4172e0-3e72-4b17-882a-56c7a61e5bf8" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/ac19047e-2664-4d32-a880-20a4a793535c" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/56a31734-d4ff-44e8-bc39-78ad87ee6ec0" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/69dc8cf7-036e-4831-89ca-1dae0eebe775" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/396236ed-a39b-448a-ad44-d76f6e6aae5c" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/63e0df64-8302-4ad1-ad31-cbac47fcea82" />
<img width="975" height="549" alt="image" src="https://github.com/user-attachments/assets/a7f67fa9-d5b8-4040-a7d1-75712d9c71c7" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/a92dcb7a-5d64-4c68-a7cc-1ed568cc7b1d" />


6. After restart click Tools then Active Directory Users and Computers.

  <img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/cdff926c-a970-4026-b32d-2de0da172959" />
<img width="1920" height="1040" alt="image" src="https://github.com/user-attachments/assets/8910decf-ca22-42ed-859e-4e54b1c2fa63" />


**Congratulations, you have now installed Active Directory and made it a Domain Controller!**


**I am excited to break, fix, and test in this environment!**

## Summary
- Used Windows Server to install Active Directory 
- Configured and assigned the IPv4 address
- Promoted our Server to a Domain Controller

Next Part: We'll create users in Powershell by running a script, and then manage the accounts and group policy!
