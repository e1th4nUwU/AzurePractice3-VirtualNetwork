# Creating a Virtual Machine using Microsoft Azure Portal
![VM Logo](img/vm-icon-23.jpg)


---------------------------------------------------------


## Requirements
- Microsoft Azure Account ( with funds or credits    )
- Microsoft Azure Suscription
- A computer using Linux, macOS or Windows
- A web browser
- Access to internet

---------------------------------------------------------

## Instructions
#### 1. Login to the [Azure Portal](https://portal.azure.com/).
#### 2. Once you're on the portal's home page, you will see something like this:
![PortalImage](img/portal-main.png)
#### 3. Inside the search bar (located at the top), look for *virtual machine* and click on it.
![Searchbar](img/searchbar.png)
#### 4. Click on *Create* and then on *Virtual machine*.
![CreateButton](img/create-vm.png)
![CreateVMButton](img/create-vm-choice.png)
#### 5. You will now need to configure your VM. The first thing you'll do is make sure the correct subscription is selected. If you're ok with the default subscription that appears, you'll then need to create/assign the VM to a resource group; in my case, I am creating one with the name *vm-group* (you can call it however you want).
![ResourceGroup](img/resource-group.png)
#### 6. Now, you have to configure the instance details: first, give it a name.
![VMName](img/vm-name.png)
#### 7. Choose a region; in my case, I'll be choosing UK South.
![Region](img/region.png)
#### 8. You can configure redundancy, security, the operating system and even the hardware for your VM. I'll leave these options as default because I won't use these VM after it's creation.
![DefaultOptions](img/default-options.png)
#### 9. Configure the credentials for your administrator account
![AdminAccount](img/admin.png)
#### 10. You are also able to configure advanced details about your VM, however, this guide will only focus on basic aspects.
![AdvancedConfiguration](img/advanced-config.png)
#### 11. If your chose Windows as your operating system, make sure to check the *Licensing* checkbox at the bottom of the *basics* page.
![License](img/license.png)
#### 12. Click on *Review + Create*.
![ReviewAndCreate](img/review-and-create.png)
#### 13. If everyting is ok and validation has passed, click on *Create*.
![Create](img/create.png)
#### 14. Deployment will begin. Please wait a few seconds.
![DeploymentInProgress](img/deployment-progress.png)
#### 15. Once deployment is complete, click on *Go to resource*.
![DeploymentComplete](img/deployment-complete.png)
#### 16. In order to connect to your VM, we will use RDP connection, so you will need to download an app for you to connect to it. In [Windows](https://www.microsoft.com/store/apps/9wzdncrfj3ps) and [macOS](https://apps.apple.com/us/app/microsoft-remote-desktop/id1295203466?mt=12), this app is called Microsoft Remote Desktop; go to the store, download it and install it. If you're on Linux, you may want to try [Remmina](https://remmina.org/) or something similar.
#### 17. Get back to the Azure Portal, inside your VM/Overview, click on *Connect* and then *RDP*.
![ConnectRDP](img/connect-rdp.png)
#### 18. Download the RDP file.
![DownloadRDP](img/download-rdp.png)
#### 19. Open the RDP file using your remote desktop application
#### 20. You will be asked if you trust the remote system. Click *Continue*.
![Continue](img/continue.png)
#### 21. Login wit the credentials you configured inside the Azure Portal (step 9).
![Login](img/login.png)
#### 22. Click *Connect anyway*.
![ConnectAnyway](img/connect-anyway.png)
#### 23. You virtual machine is ready to use!
![Ready](img/ready.png)

---------------------------------------------------------


## Congratulations ! You've just made your first VM using the Azure Portal !