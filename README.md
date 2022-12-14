<h1>Creating a virtual machine in Azure and connecting with remote desktop</h1>
This guide outlines the steps to creating a virtual machine in Azure and connecting using remote desktop.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Computer)
- Remote Desktop

<h2>Operating Systems Used </h2>

- Windows 10</b> 

<h2>Prerequisites</h2>
- Active Azure subscription

<h2>Creating a Resource Group and Virtual Machine</h2>

<p>
  <p>
    
1.) Sign into you Azure account. 
    <p>a.) First set up a Resouce Group and name the group. 
<p>
  c.) Add a new virtual machine. Set up within the Rescource group you just created. 
<p>
<img src="https://i.imgur.com/FXHatYH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
  <p>
    
1.) Set your location, image, size of your virutal computer. (Example: US East US, Windows 10 Pro with Size 2vcpus 16GB)
    <p>
      b.) Under the Administrator section, set up a user and password and be sure to keep information close. 
<P>
c.) Check box next to "Licensing". Click "Next and Create" 
<p>
<img src="https://i.imgur.com/NjYAG7u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <p>
    <p>
      
d.) Wait to confirm validation passed. Create.
      <p>
        Once finished go back to virtual computer created and view specifications. Copy the public IP address
      <p>
<img src="https://i.imgur.com/RamCGqi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
        <p>
          <p>
<img src="https://i.imgur.com/ARMiy63.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
          
On your own PC,) Go to Remote Desktop and connect to the virtual computer you just created.
                 
Paste the new IP address you copied and sign in.
                                       
                     
<img src="https://i.imgur.com/tiNgjE3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
                        <p>
You are now connected! Use the command prompt "ipconfig" to explore network protocols.
                       
Once you are finished, disconnect and delete the resource group in Azure when finished.
                            <p>
                             
