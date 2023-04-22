
<h1>Network File Sharing and Permissions</h1>
Here I will demonstrate how to share files between networks and give permissions to certain users. <br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Active Directory

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Windows Server


<h2>Steps, Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/4G6jadh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 1: 
Create 2 virtual machines(VM) in Azure. One Windows Server as the Domain with Active Directory and Windows 10 OS. Then log in to both VM by remote desktop connection.
</p>
<br />

<p>
<img src="https://i.imgur.com/WUnHgU5.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/lZ71NBC.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 2:
Create folders in the Domain Controller VM with different permissions that will be shared.
</p>
<br />

<p>
<img src="https://i.imgur.com/kLE9ltK.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
  <img src="https://i.imgur.com/dvRRcW0.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 3:
Observe that some files can be accessed and others cannot be accessed in the Client VM due to the permissions that were set. 
</p>
<br />
