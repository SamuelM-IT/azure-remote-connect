![image](https://github.com/user-attachments/assets/a1fcf701-4ea1-4c70-b31a-d62b3a5c2b1c)




<h1>Azure - Creating VMs and Connecting With Remote Desktop</h1>
This tutorial outlines the prerequisites and installation of virtual machines and connecting via remote desktop.<br />


<h2>Files you need to download</h2>

- ### [Download Now](https://remote-desktop-connection.en.softonic.com/) 📁 Remote Desktop Connection App for Windows
- ### [Download Now](https://microsoft-remote-desktop.macupdate.com/) 📁 Remote Desktop Connection App for Mac

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Create a Azure Free Account
- Create a Virtual Machine in Azure
- Create a Resource Group in Azure
- Download Remote Desktop Connection App

<h2>Installation Steps</h2>
https://azure.microsoft.com/en-us/get-started/azure-portal

![Screenshot 2025-04-04 051206](https://github.com/user-attachments/assets/618915a5-5d05-4c7b-8ee5-73385620741c)


First step after creating your Azure account, from this dashboard, hover over virtual machines and click on create Azure virtual machine.
Then, from there it will prompt up another screen and will show as the following picture below this text. 

![Screenshot 2025-04-04 051310](https://github.com/user-attachments/assets/22a59595-54d0-461a-8d2a-0d12b6dc5e3d)


If you don't have a resource group created already, you can simply create it during this process and name it whatever you like,
give a name to your virtual machine, I named mine azureuser, and for region you can select the region you're currently in, leave the 
remaining options as default. Exactly how it shows here on this image provided for this step, we have a little more to go.


![Screenshot 2025-04-04 051353](https://github.com/user-attachments/assets/3af969fb-e0e1-45fc-95b3-b29ea9055166)


For the image we chose Windows 11 because this machine will just be on a client for Windows 11, so select this image,
for the size, this depends on your needs and how fast you want your virtual machine to operate, but I chose this one, 
and for username, choose a username you won't forget and do the same for your password, keep track of it.


![Screenshot 2025-04-04 051410](https://github.com/user-attachments/assets/09b4089d-af1a-4ea8-8050-b9ea30b3f129)

Don't forget to checkmark this box for the licensing rights, after that, you can now click on "Review + create".


![Screenshot 2025-04-04 051446](https://github.com/user-attachments/assets/9717d267-d64f-491a-bc5f-a3642badcf49)


After your page has loaded, click create and the virtual machine will now begin to deploy.

![Screenshot 2025-04-04 051522](https://github.com/user-attachments/assets/f6d6cbbe-c2de-4e0b-9e0f-9576500f896d)


Once your virtual machine has been created, wait for the status to say "Running" and as you can see here on the following
image above, we now have a public ip address and we will use this in order to connect to the virtual machine we created.

![Screenshot 2025-04-04 051707](https://github.com/user-attachments/assets/646e4452-a888-4bf7-98f0-2a0f239a149a)


On your Windows PC or if you're on Mac, open up Remote Desk Connection and enter the public ip address of the virtual machine. Click "Connect". 
You will then have another screen pop up as shown on the following image down below.

![Screenshot 2025-04-04 051736](https://github.com/user-attachments/assets/8b52262a-a8f1-4668-8f2d-84a52a82f20c)

Enter the credentials of the virtual machine you created. Click "Ok".

![Screenshot 2025-04-04 051749](https://github.com/user-attachments/assets/c715a913-962f-4166-8cfd-7ee8cfbf2897)

This screen will pop up if done correctly, click "Yes".

![Screenshot 2025-04-04 051757](https://github.com/user-attachments/assets/105d2d2a-a745-47d1-a26f-f4ee9571bca6)


Connecting to the virtual machine begins...

![Screenshot 2025-04-04 051828](https://github.com/user-attachments/assets/cdfcd51a-68ce-47f9-8f0b-26a17c8af2c8)


If successful, your screen should look like this. You have now successfully created a virtual machine and connected 
via remote desktop connection. If you are done using the virtual machine, you can go back to Azure dashboard, type
virtual machines and check the box for your virtual machine and click stop or you can also delete the virtual machine if you want, or if you don't plan on no longer using it.
