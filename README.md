<h1>Active Directory Home Lab Project - Using PowerShell with script(s) to create users on Active Directory</h1>

<h2>Description</h2>
This project is a continuation of the Active-Directory-RAS-NAT-DHCP-Setup repository and we will be exploring PowerShell to create users with scripts. See diagram below for reference/network information.

<br/>
<img src="https://imgur.com/yibftVW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />

<h2>Languages and Utilities Used</h2>

- <b>PowerShell
- <b>Scripts -> https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGxkNF9jTFlMNjRJTGU1ZFdYakFsVm04akllUXxBQ3Jtc0ttTlk2MVNQSUdqeW1YQXVCWGptdXdCT2xjb2NlNnFIVElyZVR4Ym45U01iMjdTVHhuaXFpcjU0bjktZ2RQcnQzb1JKQVoxVFI1bTh3d1hjMjIwaWxFQjJNZFQtMklIVV9oNmRkdmQwS2NXSkd3ZlZ4RQ&q=https%3A%2F%2Fgithub.com%2Fjoshmadakor1%2FAD_PS%2Farchive%2Frefs%2Fheads%2Fmaster.zip&v=MHsI8hJmggI
  
<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)
- <b>Windows Server 2016</b>
- <b>Oracle VirtualBox</b>

<h2>Lab walk-through/details:</h2>

<p align="center">

On the VM, open open Internet Explorer, hit ok and paste this link onto the browser and Enter. (https://www.youtube.com/redirect?event=video_description&redir_token=QUFFLUhqbGxkNF9jTFlMNjRJTGU1ZFdYakFsVm04akllUXxBQ3Jtc0ttTlk2MVNQSUdqeW1YQXVCWGptdXdCT2xjb2NlNnFIVElyZVR4Ym45U01iMjdTVHhuaXFpcjU0bjktZ2RQcnQzb1JKQVoxVFI1bTh3d1hjMjIwaWxFQjJNZFQtMklIVV9oNmRkdmQwS2NXSkd3ZlZ4RQ&q=https%3A%2F%2Fgithub.com%2Fjoshmadakor1%2FAD_PS%2Farchive%2Frefs%2Fheads%2Fmaster.zip&v=MHsI8hJmggI) <br/>
<img src="https://imgur.com/vfDe2YZ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Proceed to site and save the file download to the desktop. <br/>
<img src="https://imgur.com/bKGJbta.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Right click and extract all on the file, find the names notepad file, and add your name to the top. Save it and close the file. <br/>
<img src="https://imgur.com/6ym3gcN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, on your taskbar/search bar, find Windows PowerShell ISE, open it and Run as Administrator. Then, click the yellow folder (open) at the top right, and import that file you just extracted and select the CREATE USERS.ps1 file. Should look like this: <br/>
<img src="https://imgur.com/OwckWqt.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Next, enter Set-ExecutionPolicy Unrestricted into the PSE command line. Then Enter, select Yes to All on the warning.  <br/>
<img src="https://imgur.com/st7oBYm.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter cd  C:\Users\a.bv\Desktop\AD_PS-master\AD_PS-master (replace my username with yours) then Enter. <br/>
<img src="https://imgur.com/pjD1nyA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Hit the green Play button at the top of the PowerShell prompt. Select Run Once on the warnings and the script will run, creating all of the users. <br/>
<img src="https://imgur.com/6BZQRIQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Upon playing, it'll create all of the users so it'll take a minute. <br/>
<img src="https://imgur.com/MK8ihI4.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After the script finishes and within a few minutes after, all users from that plain text file should be created and populated on Active Directory. Try searching for yourself or another random username.
<br/>
<img src="https://imgur.com/4bLqs5d.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In another respository a project will go over joining Windows 10 PC clients to the domain.

<br />
