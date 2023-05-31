<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
Microsoft Azure is a powerful cloud platform that provides various tools and services like virtual machines, storage, AI, and easy project deployment. It helps businesses and individuals increase productivity, gain valuable insights from data, and effortlessly scale applications to meet their needs. With Azure, you can harness the potential of the cloud to drive innovation and achieve your goals with greater efficiency.
  
<h1>Setup a Subscription, Resource Group, Storage Account, and Virtual Machine in Azure</h1>

This guide is meant to demonstrate a step-by-step process for any beginner on how to create a FREE* Azure account, create a Resource Group, a Storage Account, build a Virtual Machine and how to connect to it using Remote Desktop.

<h2>Requirements</h2>

- Computer w/ Internet Connection
- Credit Card (Required for free Azure credits)
- Remote Desktop Connection (Windows) / Microsoft Remote Desktop (Mac)
  
<h2>Step Process</h2>

<h3>&#9312; Create a FREE* Azure Account</h3>

Go to [https://azure.microsoft.com/en-us/free/](https://azure.microsoft.com/en-us/free/)
- Click "Start Free".
- Follow the prompt to create an account.
  - You WILL need to put in your credit card information to receive the free $200 worth of Azure credits!
    <div> It will not charge you, <b>but only for 30 days!</b>
- Once completed, click on <a href="https://portal.azure.com/">Go to the Azure Portal (portal.azure.com)</a>.

<img src="https://i.imgur.com/FklBT6F.jpg" height="64%" width="64%" alt="Azure Free Account"/>
<hr>

<h3>&#9313; Create a Resource Group</h3>

- In the Search Box at the top header, type and select "Resource groups".
  - If "Resource groups" is already listed on the front page, then you can simply click on it, rather than manually searching.
 
<img src="https://i.imgur.com/gza489d.jpg" height="64%" width="64%" alt="Azure Step 2-1"/>

- Click "Create" on the top left menu, OR simply press "Create resource group" in the center box (assuming one doesn't exist yet).

<img src="https://i.imgur.com/5Jo1cEg.jpg" height="64%" width="64%" alt="Azure Step 2-2"/>

- Name your "Resource group" to whatever you want (this example uses **RG-01**).
- Change the "Region" to a location that is closest to you (this example uses **(US) West US 3**).
- Skip everything else and clicl "Review + Create" on the lower left, which you should have "Validation passed" on the next page.
- Click "Create".

<img src="https://i.imgur.com/BSiQM05.jpg" height="100%" width="100%" alt="Azure Step 2-3"/>

<hr>
<h3>&#9314; Create a Storage Account</h3>

- In the Search Box at the top header, type and select "Storage accounts".
  - If "Storage accounts" is already listed on the front page, then you can simply click on it, rather than manually searching.
  
<img src="https://i.imgur.com/HMUaR98.jpg" height="70%" width="70%" alt="Azure Step 3-1"/>

- Same with Resource Groups, click on "Create Storage account".

<img src="https://i.imgur.com/sGDY2Im.jpg" height="70%" width="70%" alt="Azure Step 3-2"/>

- Use the same resource group that was just created (this example uses **RG-01**).
- Create a unique name for the storage account that hasn't already been taken (this example uses **saname01**).
- Choose the same region (this example uses **(US) West US 3**).
- Skip everything else and click "Review", then "Create".

<img src="https://i.imgur.com/07sG8Z6.jpg" height="100%" width="100%" alt="Azure Step 3-3"/>
<img src="https://i.imgur.com/wLSVgnw.jpg" height="100%" width="100%" alt="Azure Step 3-4"/>

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
 
     

<h3>&#9316; Connect to the Virtual Machine via Remote Desktop</h3>

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
  
