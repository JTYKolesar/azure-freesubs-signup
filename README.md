<p align="center">
<img src="https://i.imgur.com/1DDZ4Ui.png" height="50%" width="50%" alt="Microsoft Azure Logo"/>
</p>
<p align="justify">
Microsoft Azure is a powerful cloud platform that provides various tools and services like virtual machines, storage, AI, and easy project deployment. It helps businesses and individuals increase productivity, gain valuable insights from data, and effortlessly scale applications to meet their needs. With Azure, you can harness the potential of the cloud to drive innovation and achieve your goals with greater efficiency.
  
<h1>Setup a Subscription, Resource Group, Storage Account, and Virtual Machine in Microsoft Azure</h1>

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
<hr>
<h3>&#9315; Create a Virtual Machine</h3>
     
- In the Search Box at the top header, type and select "Storage accounts".
  - If "Storage accounts" is already listed on the front page, then you can simply click on it, rather than manually searching.
<img src="https://i.imgur.com/6DdH3MD.jpg" height="70%" width="70%" alt="Azure Step 4-1"/>

- Click "Create", then select "Azure Virtual Machine"
<img src="https://i.imgur.com/tiC5aA4.jpg" height="70%" width="70%" alt="Azure Step 4-2"/>

- Use the same resource group (this example uses **RG-01**)
- Name your virtual machine however you want (this example uses **virtualmachine01**)
- Use the same region (this example uses **(US) West US 3**)
- Choose your "Image" (this example uses **Windows 10 Pro, version 22H2 - x64 Gen2**)
- Choose a "Size" (this example uses **Standard_E2s_v3 - 2 vcpus, 16 GiB memory**)
- Create any username and password of your choice (this example uses the username: **vmuser**)
  - Make sure NOT to forget these credentials.
- Check the "Licensing" checkbox.
- Click "Review + create".
  - Once validation passed, click "Create".
<img src="https://i.imgur.com/UaviYRo.jpg" height="70%" width="70%" alt="Azure Step 4-3"/>
<img src="https://i.imgur.com/mcix7TW.jpg" height="70%" width="70%" alt="Azure Step 4-4"/>

<hr>
<h3>&#9316; Connect to the Virtual Machine via Remote Desktop</h3>

- Go to your Virtual Machine that was just created and COPY the public IP address (located on the right side).
<img src="https://i.imgur.com/Cr02uvs.jpg" height="100%" width="100%" alt="Azure Step 5-1"/>

- Press the Windows Key (or Start Button), type and select "Remote Desktop Connection".
- Input the virtual machine's Public IP Address and click Connect.
- Enter the username and password from Step 4 above, then click OK.
  
- Macintosh users will have to take a different approach:
  - Download "Microsoft Remote Desktop", and Open it.
  - Click Add PC", input the public IP address, then select "Add".
  - Double-click on the virtual machine, then enter the username and password from Step 4 above.
  - Select "Continue".
<img src="https://i.imgur.com/rP1uKCe.jpg" height="64%" width="64%" alt="Azure Step 5-2"/>

- A prompt will appear about the identity cannot be verified; just press "YES".
<img src="https://i.imgur.com/3YxlS2G.jpg" height="64%" width="64%" alt="Azure Step 5-3"/>

- Toggle any settings you want, then click "Accept".
<img src="https://i.imgur.com/VlNH4O9.jpg" height="64%" width="64%" alt="Azure Step 5-4"/>

🎊 CONGRATULATIONS! You have created your first virtual machine within Azure! 🎊
<img src="https://i.imgur.com/PpLmQO7.jpg" height="80%" width="80%" alt="Azure Step 5-5"/>


<h3>NOTE:</h3>

- To retain your free Azure credits, make sure you **DELETE ALL** your resources and resource groups after finishing!
  
