<p align="center">
<img src="https://i.imgur.com/tnNzW2L.png" alt="ProtoVPN"/>
</p>

<h1>VPN Setup & Usage</h1>
VPN's can securely link two computers (or networks) together across an insecure network such as the internet, allowing them to send encapsulated and encrypted data to each other.
This tutorial outlines how to use a VPN using a virtual machine with Azure.<br />


<h2>Environments and Technologies Used</h2>

- Microsoft Azure 
- Windows Virtual Machine
- Remote Desktop
- ProtonVPN

<h2>Operating Systems Used </h2>

- Windows 10</b>

<h2>Objectives</h2>

- Create Virtual Machine
- Observe IP adress before with no VPN
- Download and install ProtonVPN
- Observe IP address after with VPN

<h2>Before We Begin</h2>
Browse to https://whatismyipaddress.com and take notes of your current ipaddress in a text file or note pad

<img src="https://i.imgur.com/PYJ4z8V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<h2>Create Virtual Machine in Azure</h2>

- Create a Resource Group > Name- RG-VPN

- Create Virtual Machine > Create Microsoft 10 in another geographic location (try a different country) > Setup your login > Create

<img src="https://i.imgur.com/NRrbAIn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Log into the VM with Remote Desktop

<img src="https://i.imgur.com/7eAH06B.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Browse to https://whatismyipaddress.com and take note of this in your text file or note pad

<img src="https://i.imgur.com/L1FDvtl.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Sign up and Download ProtonVPN </h2>

Download and install ProtonVPN on your device. You can do this by visiting the [ProtoVpn](https://protonvpn.com/?utm_campaign=us-all-2a-vpn-gro_src-g_acq-branded&utm_medium=src_ad&utm_source=google.com&utm_content=127281928056&utm_term=proton+vpn) clicking this link and following the installation instructions provided.


<img src="https://i.imgur.com/gqMtiKH.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<img src="https://i.imgur.com/mzDb4dx.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<h2>Observe IP Address with VPN</h2>

- Select a country in which you woulid like to connect. 
 
<img src="https://i.imgur.com/tYxZLQE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


- Browse to https://whatismyipaddress.com AGAIN  with VPN and take note of this in your text file or note pad. Try browsing other websites and see if there is anything different about the website in relation to the location of your VPN Server.


<img src="https://i.imgur.com/9SZlVIP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


<img src="https://i.imgur.com/NHEiwmQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>


