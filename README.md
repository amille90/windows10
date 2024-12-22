<p align="center">
<img src=https://i.imgur.com/wWxNb0n.png"/>
</p>

<h1>Windows 10 Virtual Machine Configuration in Azure</h1>
This project tutorial outlines the set up and configuaration of a Windows 10 Virtual Machine inside of Microsoft Azure.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
  

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Computer Desktop/Laptop
- Azure Account
- Remote Desktop
- Wifi Connection

<h2>Configuration Steps</h2>
Step 1: Go onto Azure's homepage and click on Resource Group.

<p>
<img src="https://i.imgur.com/LFTDxBx.png"/>
</p>
<p>
<br />
Step 2: Under project details give your resource group a name and select an appropiate region for your location, then press review and create.
<p>
<img src="https://i.imgur.com/in6UssU.png"/>
</p>
<p>
Step 3: A 'Validation banner' should pop up next on your screen.
</p>
<br />

<p>
<img src="https://i.imgur.com/xF6dR3g.png"/>
</p>
<p>
</p>

Step 4: Go to the Virtual Machine page.

<img src="https://i.imgur.com/kg82JDY.png"/>
</p>
<p>

<br />
Step 5: Click on create and in the drop down menu click on Azure Virtual machine.
<p>
<img src="https://i.imgur.com/vLzuHUy.png"/>
</p>
<p>

<br />
Step 6: Select the Resource Group previously created in the first and second steps.
<p>
<img src="https://i.imgur.com/AeI8Y8e.png"/>
</p>
<p>

</p>
<br />
Step 7: Name the Virtual Machine 'Windows10-vm'.
<p>
<img src="https://i.imgur.com/Wjq0ReZ.png"/>
</p>
<p>

</p>
<br />
Step 8: Set your region appropiate to your location.
<p>
<img src="https://i.imgur.com/4fKdirn.png"/>
</p>
<p>

</p>
<br />
Step 9: Select an availabity zone.
<p>
<img src="https://i.imgur.com/QWNk0Ie.png"/>
</p>
<p>

</p>
<br />
Step 10: For image select Windows 10 Pro, version 22H2-x64 Gen2.
<p>
<img src="https://i.imgur.com/zEIlo59.png"/>
</p>
<p>

</p>
<br />
Step 11: For size choose the Standard_D4s_v3-4 vcpus, 16 GiB memory.
<p>
<img src="https://i.imgur.com/7Cht9tk.png"/>
</p>
<p>

</p>
<br />
Step 12: Underneath Administrator Account make sure to fill in a username and password. These will be the credentials used to log into the Windows 10 remote desktop.
<p>
<img src="https://i.imgur.com/g4Ht9iY.png"/>
</p>
<p>

</p>
<br />
Step 13: Next check off the confirm checkbox under Licensing then click the 'Next: Disks' button.
<p>
<img src="https://i.imgur.com/B3sNUyF.png"/>
</p>
<p>

</p>
<br />

Step 14: Click on the networking button and on the networking page underneath virtual network click on create new to create a new virtual network.
<p>
<img src="https://i.imgur.com/wQiEfwh.png"/>
</p>
<p>

</p>
<br />

Step 15: The 'Create Virtual Network' page should pop up. In the name box call it "lab2-vnet" or you can give it your own name then press ok.
<p>
<img src="https://i.imgur.com/Z5i4a7v.png"/>
</p>
<p>

</p>
<br />

Step 16: Next you'll be reverted back to the networking page and from there you can press review and create.
<p>
<img src="https://i.imgur.com/1Y3I0cE.png"/>
</p>
<p>

</p>
<br />

Step 17: Validation page should come up next, press create.
<p>
<img src="https://i.imgur.com/hHp0J7G.png"/>
</p>
<p>

</p>
<br />

Step 18: After pressing create, the deployment in progress page should come up. This step usually take a minute or two to process.
<p>
<img src="https://i.imgur.com/mqNK4G6.png"/>
</p>
<p>

</p>
<br />

Step 19: Deployment should be complete.
<p>
<img src="https://i.imgur.com/OPC30bi.png"/>
</p>
<p>

</p>
<br />

Step 20: Next, go back to resource group.
<p>
<img src="https://i.imgur.com/Ytji0OM.png"/>
</p>
<p>

</p>
<br />

Step 21: Here you will see where you created your first resource group.
<img src="https://i.imgur.com/kj986qY.png"/>
</p>
<p>

</p>
<br />

Step 22: Next, go back to Virtual Machines and you will see the very first virtual machine you've created within Azure.
<p>
<img src="https://i.imgur.com/jjUHF8h.png"/>
</p>
<p>

</p>
<br />

<p>
<img src="https://i.imgur.com/MBDYBEu.png"/>
</p>
<p>

</p>
<br />













