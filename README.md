
<p align="center">
<img width="272" height="185" alt="image" src="https://github.com/user-attachments/assets/3598555c-e728-4e21-820d-1b5ac9981fa5" />

 
  # Installing and Configuring an Active Directory Domain

## Description
This project demonstrates how to set up a domain in Active Directory using Server Manager. It covers installing AD DS, promoting the server to a domain controller, configuring DNS, and joining computers to the domain. 

## Utiliities & Enviroments Used
- Server Manager
- Active Directory Users and Computers
- Windows Sever 2025
- Windows 11
## Project Walkthrough:
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/f6a5f956-6939-4be1-864d-55ebe8ce7ae0" />
<img width="1326" height="743" alt="image" src="https://github.com/user-attachments/assets/b1c23024-4454-47bc-8a86-06faade54cc8" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/7404f844-acde-4d7d-b91f-6849d3378004" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/7ea6312d-d611-40d5-bd2e-ae25c62052c5" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/269a7af0-d712-4dff-af26-811e924233f7" />
<img width="975" height="548" alt="image" src="https://github.com/user-attachments/assets/a210acd0-504a-4899-9807-801e06d6cd9a" />

## Configure Network Adapters

<img width="975" height="530" alt="image" src="https://github.com/user-attachments/assets/0ae42d66-e27b-4292-b83b-40de86a2bbe4" />
<img width="975" height="944" alt="image" src="https://github.com/user-attachments/assets/defc4631-9160-4116-a4fc-4a7811818c18" />
<img width="975" height="948" alt="image" src="https://github.com/user-attachments/assets/2614fd3b-de45-435c-9914-a7f55698bfae" />
<img width="975" height="947" alt="image" src="https://github.com/user-attachments/assets/3a1cac27-f655-4a0f-a77b-b5ef2f4325a6" />
If you haven’t done so, do the same thing to the Window’s 11 VM we created. If not repeat the previous steps.

### Finding the DHCP Address

<img width="470" height="302" alt="image" src="https://github.com/user-attachments/assets/0a6971ac-86cd-4052-8918-4a274de0bfc4" />
<img width="941" height="874" alt="image" src="https://github.com/user-attachments/assets/d33dd068-0279-46a7-b8dc-9ca528fce4b2" />
<img width="713" height="539" alt="image" src="https://github.com/user-attachments/assets/4b4dddf6-ff17-490d-83e2-c96a1fa491a5" />

## Assign Static IP to Server

<img width="975" height="946" alt="image" src="https://github.com/user-attachments/assets/f4e1cb9c-7ebd-4c19-b50c-6e1f3cf70d7a" />
<img width="975" height="513" alt="image" src="https://github.com/user-attachments/assets/d92ad74d-b6cd-45c4-bb1e-c1eef3e11337" />
<img width="764" height="656" alt="image" src="https://github.com/user-attachments/assets/487e2a3d-30e0-4f52-a000-a62c300c8cb3" />
<img width="606" height="883" alt="image" src="https://github.com/user-attachments/assets/1fb78588-a470-4dcd-bfed-3da45d25aad1" />


<img width="975" height="603" alt="image" src="https://github.com/user-attachments/assets/2bc77c67-34a9-4096-8d3e-504bbafe5445" />

Server now has a static IP
- To check if has a static IP search CMD at the bottom.

  <img width="975" height="876" alt="image" src="https://github.com/user-attachments/assets/43768880-05a3-40a5-95df-c99a5888bd8e" />
- Run ipconfig and the IPv4 address should be the IP we assigned to the server.

  <img width="975" height="555" alt="image" src="https://github.com/user-attachments/assets/eab1f3c8-534b-4520-a544-344dc2f919f9" />

## Installing Active Directory
1. Click "Add roles and features".
<img width="975" height="810" alt="image" src="https://github.com/user-attachments/assets/94a589f0-1cce-46a7-a29b-8c01abb59f98" />
<img width="975" height="692" alt="image" src="https://github.com/user-attachments/assets/dce86425-abc2-4afd-8472-202c9648d811" />
<img width="975" height="694" alt="image" src="https://github.com/user-attachments/assets/ac4aad8e-2db4-436f-9654-59a3e0fe239d" />
<img width="975" height="689" alt="image" src="https://github.com/user-attachments/assets/4374d695-ec94-4114-9c24-c47f12fbb364" />
2. Click Active Directory Domain Services and Add Features.
   
<img width="975" height="791" alt="image" src="https://github.com/user-attachments/assets/6fd33518-a0d8-475d-8ce9-aa54600fe7c1" />
<img width="975" height="690" alt="image" src="https://github.com/user-attachments/assets/dd17f9fa-baea-4fb6-8e41-f714b5fce462" />
<img width="975" height="699" alt="image" src="https://github.com/user-attachments/assets/71a55491-86fa-48de-8ad1-1c665737c145" />
<img width="975" height="696" alt="image" src="https://github.com/user-attachments/assets/ff77e408-4e2b-486a-bf59-9480c6dd1500" />

##  Promote Server to Domain Controller
1. Click the yellow warning indicator for the Post-deployment Configuration.

   <img width="955" height="796" alt="image" src="https://github.com/user-attachments/assets/7a6e6347-a3b7-4b07-9533-ee29afa7cd57" />
<img width="975" height="817" alt="image" src="https://github.com/user-attachments/assets/55526a35-97e9-43e0-9ab6-4ca7c72543af" />
<img width="975" height="815" alt="image" src="https://github.com/user-attachments/assets/d21a965a-3102-465a-bb0a-b49bb0ebffff" />
<img width="975" height="717" alt="image" src="https://github.com/user-attachments/assets/b624eff7-8d6a-4bbb-9e1c-9a716a6e960b" />
<img width="975" height="815" alt="image" src="https://github.com/user-attachments/assets/879a01af-ce00-4736-a620-9ac7c132fcaf" />
<img width="975" height="826" alt="image" src="https://github.com/user-attachments/assets/5aa16923-f246-4719-a531-0bf88438de25" />
<img width="975" height="818" alt="image" src="https://github.com/user-attachments/assets/9af5dd64-5254-4612-a673-57c2db62d09d" />
<img width="975" height="725" alt="image" src="https://github.com/user-attachments/assets/23117548-3777-405b-9e96-9b0f272d9655" />
- Once complete it will restart.
<img width="975" height="389" alt="image" src="https://github.com/user-attachments/assets/0910de7b-618a-4db8-a328-082140364bc5" />
- Will now show "Lab/admin".

  <img width="975" height="684" alt="image" src="https://github.com/user-attachments/assets/56d20db9-ba71-4857-b97c-f6a739753e07" />
<img width="975" height="720" alt="image" src="https://github.com/user-attachments/assets/88558e4d-67e7-4208-a071-575ce8250fef" />

**Congratulations, you have now installed Active Directory and made it a Domain Controller!**

## Summary
- Used Windows Server to install Active Directory 
- Configured and assigned the IPv4 address
- Promoted our Server to a Domain Controller

Next Part: 
