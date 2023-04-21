<p align="center">
<img src="https://i.imgur.com/Us74xWW.png" height="40%" width="40%" alt="Microsoft Azure Logo"/>
</p>

<h1>Create an Azure Account and Deploy a Virtual Machine</h1>
Microsoft Azure is a cloud computing platform with numerous products and services. This guide will demonstrate how to create an account, utilize the portal, and create a virtual machine.

<h2>Environments and Technologies Used</h2>

- Microsoft Azure
- Microsoft Remote Desktop (macOS) for virtual machines

<h2>Configuration Steps</h2>

- Step 1: Create Azure Account
- Step 2: Azure portal and resource group
- Step 3: Create a virtual machine
- Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS

<h3>Step 1: Create Azure Account</h3>
First step is to create an Azure account. You can create an account with $200 of free credit for a month. 

<br>
<br>

Create an Azure account [here](https://azure.microsoft.com/en-us/free/).

<p align="center">
<a href="https://imgur.com/t51tZPL"><img src="https://i.imgur.com/t51tZPL.png" title="source: imgur.com" /></a>
  
<p align="center">
<a href="https://imgur.com/PjLTm0e"><img src="https://i.imgur.com/PjLTm0e.png" title="source: imgur.com" /></a>
</p>

Follow all the prompts to create the account. A credit card will be needed but will not be charged until the $200 credit runs out or the account has been active for a month. After you create your account, you are now a tenant in Azure!

<h3>Step 2: Azure portal and resource groups</h3>

Now that the account has been created, let's go over how to navigate the Azure portal. The portal is where you can find all the products/resources and manage your subscriptions. It is a user friendly interface.

The portal is located [here](https://www.portal.azure.com).

<p align="center">
<a href="https://imgur.com/cNALhIR"><img src="https://i.imgur.com/cNALhIR.png" title="source: imgur.com" /></a>
</p>

In order to utilize some of the services in Azure, a resource group needs to be created. Resource groups store all resources that you are utilizing in Azure. This example will show how to deploy a Windows 10 virtual machine.

<p align="center">
<a href="https://imgur.com/A3rHrtM"><img src="https://i.imgur.com/A3rHrtM.png" title="source: imgur.com" /></a>
</p>

When ready, click create resource groups. From there, you will need to name your resource group and select the region. The region will determine which Azure data center will be utilize. (US) West 3 was chosen for this example. Click "Review + Create" once finished

<p align="center">
<a href="https://imgur.com/RcwCnMD"><img src="https://i.imgur.com/RcwCnMD.png" title="source: imgur.com" /></a>
</p>

<h3>Step 3: Create a virtual machine</h3>
Next step is to create a virtual machine. At the portal, click on virtual machine and click create. Once at the create virtual machine menu, follow all the instructions. Make sure to fill out all the areas that have a red asterisk on them (resource group, name, etc.). Don't worry about the other tabs such as disks and networking as they will be prefilled. Make sure you remember the username and password! Once this is all completed, your virtual machine will appear in your resource group. 

<p align="center">
<a href="https://imgur.com/1CLm5Zt"><img src="https://i.imgur.com/1CLm5Zt.png" title="source: imgur.com" /></a>
</p>

<p align="center">
<a href="https://imgur.com/QrqmPpC"><img src="https://i.imgur.com/QrqmPpC.png" title="source: imgur.com" /></a>
</p>

<h3>Step 4: Connect to virtual machine using Microsoft Remote Desktop on macOS</h3>
The final step to this process is accessing the virtual machine using Microsoft Remote Desktop. <p>Windows users hit the windows key then type remote desktop</p> <br>

<p align="center">
<a href="https://imgur.com/mF14wYf"><img src="https://i.imgur.com/mF14wYf.png" title="source: imgur.com" /></a>
</p>

<p>Mac users will have to download the application in the App Store. </p>

<p align="center">
<a href="https://imgur.com/7XCPKZT"><img src="https://i.imgur.com/7XCPKZT.png" title="source: imgur.com" /></a>
</p>

In order to connect to the virtual machine, first you need the public IP address. You can find this on the right hand side of this menu.

<p align="center">
<a href="https://imgur.com/I6yI17Y"><img src="https://i.imgur.com/I6yI17Y.png" title="source: imgur.com" /></a>
</p>

Within the remote desktop window . Copy and paste the public IP address of the virtual machine that was created when prompted. Type in the username and password the click connect. 

<p align="center">
<a href="https://imgur.com/lC4x42z"><img src="https://i.imgur.com/lC4x42z.png" title="source: imgur.com" /></a>
</p>

<p align="center">
<a href="https://imgur.com/qM6khbd"><img src="https://i.imgur.com/qM6khbd.png" title="source: imgur.com" /></a>
</p>

That's it! 
