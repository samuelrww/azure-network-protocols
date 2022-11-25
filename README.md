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
    
Sign into you Azure account. 
    <p>First set up a Resouce Group and name the group. 
<p>
  Add a new virtual machine. Set up within the Rescource group you just created. 
<p>
<img src="https://i.imgur.com/FXHatYH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<p>
  <p>
    
Set your location, image, size of your virutal computer. (Example: US East US, Windows 10 Pro with Size 2vcpus 16GB)
    <p>
      Under the Administrator section, set up a user and password (write down) 
<P>
Check box next to "Licensing". Click "Next and Create" 
<p>
<img src="https://i.imgur.com/NjYAG7u.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <p>
    <p>
      
Wait to confirm validation passed. Create.
      <p>
        Once finished go back to virtual computer created and view specs. Copy public IP address
      <p>
<img src="https://i.imgur.com/RamCGqi.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
        <p>
          <p>
<img src="https://i.imgur.com/ARMiy63.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
            <p>
              <p>
            
<h2>Connecting to the Virtual Computer Remotely</h2>
            <p>
          <p>
On your own PC,(Windows OS) Go to Remote Desktop and connect to the virtual computer you just created.
                    <p>
                      
Paste the new IP address you copied and sign in.
                                        <p>
                      <p>
<img src="https://i.imgur.com/tiNgjE3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/> 
                        <p>
You are now connected. Use the command prompt "ipconfig" to explore network protocols.
                          <p>
Once you are finished, disconnect and delete the resource group in Azure when finished.
                            <p>
                              End.
