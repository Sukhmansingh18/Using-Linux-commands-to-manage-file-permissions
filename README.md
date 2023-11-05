<h1>Using Linux commands to manage file permissions</h1>



<h2>Description</h2>
Using linux commands during this project to manage file permissions. While learning and practising various commands on Linux to assign or managing file permissions.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
Checking file permissions in Projects directory <br/>
<img width="1440" alt="Screenshot 2023-11-05 at 10 22 36 AM" src="https://github.com/Sukhmansingh18/Using-Linux-commands-to-manage-file-permissions/assets/139189335/c1d8b203-89f2-4b74-a2b1-433613cf1352">
<br />
 <h2>Describe the permissions string</h2>
Permission string contains 10 Character String that conveys permission.
drwxrwxrwx
 d -- Stands for directory, (-) for file. <br />
 First three character shows permission for User -- that has read,write and execute permission. <br />
 Second three character shows permission for Group. <br />
 Third three character shows permission for Others. <br />
<br />

<br />
The file project_m.txt is a restricted file and should not be readable or writable by the group or other; only the user should have these permissions on this file. 
<br/>
<img width="717" alt="Screenshot 2023-11-05 at 10 39 25 AM" src="https://github.com/Sukhmansingh18/Using-Linux-commands-to-manage-file-permissions/assets/139189335/dd537555-69f8-4d27-a31d-433fc169845e">
<br />
<br />
Changing permissions for hidden files <br/>
The file .project_x.txt is a hidden file that has been archived and should not be written to by anyone.<br />

<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
