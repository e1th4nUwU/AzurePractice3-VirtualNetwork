# Creating a Virtual Network using Microsoft Azure Portal
![VirtualNetworkLogo](img/virtual-network-icon.png)


---------------------------------------------------------


## Requirements
- Microsoft Azure Account ( with funds or credits    )
- Microsoft Azure Suscription
- A web browser
- Access to internet

---------------------------------------------------------

## Instructions
#### 1. Login to the [Azure Portal](https://portal.azure.com/).
#### 2. Once you're on the portal's home page, you will see something like this:
![PortalImage](img/portal-main.png)
#### 3. Inside the search bar (located at the top), look for *virtual networks* and click on it.
![Searchbar](img/searchbar.png)
#### 4. Click on *Create*.
![CreateButton](img/create-button.png)
#### 5. You will first need to choose the suscription and resource group where you'll be storing your virtual network. In my case, I am creating a new resource group and I'll be storing my network in there.
![SubscriptionAndResourceGroup](img/virtual-network-group.png)
#### 6. Now, you have to configure the instance details: you just need a name and the region where you'll be hosting your virtual network.
![InstanceDetails](img/instance-details.png)
#### 7. Inside the IP Addresses tab, you are able to configure the address space as well as subnets. I won't be configuring anything in here.
![IPAddresses](img/ip-addresses.png)
#### 8. Inside the security tab, you may also add protection to your network via Azure Bastion Host, DDoS  Protection and Firewall.
![Security](img/security.png)
#### 9. In the tags section, you can add some tags in case you need them.
![Tags](img/tags.png)
#### 10. Finally, click on *Review + create*.
![ReviewAndCreate](img/review-and-create.png)
#### 11. If the validation passed, click on *Create*.
![Create](img/create.png)
#### 12. Once deployment has been completed (which is usually really fast), you will se something like this:
![DeploymentCompleted](img/deployment-complete.png)
#### 13. Click on *Go to resource*.
![GoToResource](img/go-to-resource.png)
#### 14. Your virtual network is now available and ready for configuration.
![VirtualNetworkDashboard](img/vn-dashboard.png)

---------------------------------------------------------


## Congratulations ! You've just made your first virtual network using the Azure Portal !W
