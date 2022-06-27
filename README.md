<h1>File Integrity Monitor</h1>

 <h2>Description</h2>
Project consisted of creating a custom/proof of concept File Integrity Monitor (FIM). PowerShell was used to create an integrity baseline of target files/folders using the SHA-512 hashing algorithm while continuously making comparison of actual files vs baseline, raising alerts if any deviation occurred.
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Project Walk-Through:</h2>

<p align="center">
Ask User What They Want To Do: <br/>
<img src="https://i.imgur.com/mNmW1jE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>

<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/mNmW1jE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
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
