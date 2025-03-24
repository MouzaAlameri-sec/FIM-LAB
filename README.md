<h1> Using Wazuh platform to enforce File Integrity Monitoring </h1>



<h2>Description</h2>
This lab project is part of my preparation for the CompTIA Security+ certification. It’s a hands-on project that implements key concepts like SIEM (Security Information and Event Management) — a system that monitors and analyzes logs to detect suspicious behavior. This includes file monitoring, where alerts are triggered if files are modified, accessed, or deleted unexpectedly.

For this project, we’ll be using Wazuh, an open-source SIEM platform that provides real-time threat detection, log analysis, and security monitoring.

NOTE. Screenshots would include name and date to ensure integrity of work. (This lab is done in ACI Learning environment) To test this lab realistically you would need to set up the envrionmenets used in vmware / virtual mechine. 
 
WORK IN PROGRESS... 
-
<br />



<h2>Environments Used </h2>
Windows Server 2022 - Domain Controller
Windows 11 PRO - Domain Member Workstation
Alma Linux 9.1 - Stand-alone Linux Server

- <b>    </b> 

<h2>Program walk-through:</h2>

<p align="center">
: <br/>
<img src="https://i.imgur.com/gdWWtaa.png" height="80%" width="80%" alt="check status of wazuh in linux / NOTE. wazuh manger is in linux it checks if its active there the light weight wazuh is distrubuted in the other devices"/>
<br />
<br />
check status of wazuh in linux / NOTE. wazuh manger is in linux it checks if its active there the light weight wazuh is distrubuted in the other devices:  <br/>
<img src="https://i.imgur.com/dzUwN12.png" height="80%" width="80%" alt="start and check again"/>
<br />
<br />
start and check again: <br/>
<img src="https://i.imgur.com/qaubXpc.png" height="80%" width="80%" alt="entre ip of linux in firefox "/>
<br />
<br />
enter ip of linux in firefox and log in and wait for checks :  <br/>
<img src="https://i.imgur.com/ZUxH36V.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Add new agent in wazuh, and fill in select groups defualt and connect it to the cost environment [domain member]:  <br/>
<img src="https://i.imgur.com/4paOipP.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
This command connects linux and window member.  :  <br/>
