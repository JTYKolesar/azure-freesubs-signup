<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
Microsoft Azure is a comprehensive and flexible cloud computing platform that empowers businesses to build, deploy, and manage applications and services across a vast network of data centers. With its robust suite of tools and services, Azure provides organizations with the scalability, reliability, and security needed to accelerate growth, drive innovation, and achieve their digital transformation goals.<div>
<h1>How to Setup a Subscription, Resource, and Virtual Machine in Azure</h1>

This guide is meant to demonstrate a step-by-step process on how to create a FREE* Azure account, setup a Resource Group, build a Virtual Machine, and how to connect to the VM using Remote Desktop.

<h2>Requirements</h2>

- Computer w/ Internet Connection
- Credit Card (Required for free Azure credits)
- Remote Desktop Connection (Windows) / Microsoft Remote Desktop (Mac)
  
<h2>Procedure</h2>

<h3>&#9312; Create your FREE* Azure Account</h3>

Create a FREE* Azure account [here](https://azure.microsoft.com/en-us/free/).
- Select Start Free
- Follow the prompt to create the account 
     - You will need to put in your credit card information, but you will get $200 worth of Azure credit and will have 30 days to use those credits. You will not be charged until then
- Finish the prompt, click Go to Azure Portal, and you are ready to start with Azure!
     - You may also go to [portal.azure.com](https://www.portal.azure.com) to start


<p align="center">
<img src="https://i.imgur.com/rk4SD27.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/f1eRIx4.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
<hr>

<h3>&#9313; Create a Resource Group</h3>

- Go to the search bar at the top and search "resource group"
- Select Create Resource Group
- You will need to name the resource group and select the region 
- Select Review + Create on the lower left
    - For this example, we will be using RG-Lab-1 for the name and (US) West 3 for the region

<p align="center">
<img src="https://i.imgur.com/Afnk87u.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/yBBln5a.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
<hr>
<h3>&#9314; Create a Storage Account</h3>

- Go to the search bar and search "storage account"
- Select Create Storage Account
- You will need to select the same resource group, the same region, and create a name for the storage group
    - For this example, we will name the storage group "rglab1"
    - Use the same resource group and region as step 2
- Select Review, then Create

<p align="center">
<img src="https://i.imgur.com/zhb3GHZ.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/7ryNBQg.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>


<h3>&#9315; Create a Virtual Machine</h3>
     
- Go to the search bar and search "virtual machine"
- Select Create, then select Azure Virtual Machine
- You will need to select the same resource group, the same region, and create a name for the virtual machine
    - For thise example, we will name the virtual machine "virtualmachine"
    - Use the same resource group and region as steps 2 and 3

<p align="center">
<img src="https://i.imgur.com/y0RafHM.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/PCJ3QAr.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 



* You will then need to select the image and disk size
    - For image we will use Windows 10 Pro
    - For size, select See All Sizes and select Standard D2as_v4
* You will then need to make a username and password
    - For username, we will use "labuser"
    - Create your own password
* Click the box under licensing and finally click Review + Create 


<p align="center">
<img src="https://i.imgur.com/p9UJXND.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/GHBDae0.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>
 
     

<h3>&#9316; Connect to the Virtual Machine</h3>

- First, you will need to find the public IP address of your virtual machine
   - Select the virtual machine we created and the public IP address will be on the right-hand side of the screen
   - Copy the public IP address

<p align="center">
<img src="https://i.imgur.com/T4Oc2RX.png" height="80%" width="80%" alt="Azure Free Account"/>

* Mac Users 
   - Download Microsoft Remote Desktop
   - Open the application and click Add PC
   - Paste the public IP address and select Add
   - Double-click on the virtual machine and enter the username and password from step 4
   - Select Continue
   
* Windows Users
     - Open and use Remote Desktop
     - Paste the public IP Address and select Connect
     - Enter the username and password from step 4
     - Select OK
  
     
     
 <p align="center">
<img src="https://i.imgur.com/14pPOdv.png" height="70%" width="70%" alt="Azure Free Account"/> <img src="https://i.imgur.com/Og3LKyd.png" height="70%" width="70%" alt="Azure Free Services"/>
</p>





🎉Congratulations! You have created your first virtual machine within Azure!🎉

<p align="center">
<img src="https://i.imgur.com/rEBpL8Y.png" height="80%" width="80%" alt="Azure Free Account"/>

<h3>Tip</h3>

-  If you want to save your free $200 credits, make sure you delete ALL your resources and resource groups after finishing!    
  
