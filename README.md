# OS <p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Install OS-Ticket zip file
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

![image](https://github.com/user-attachments/assets/a8a6cb2f-127c-4682-acda-11dd7d7ecba0)



<p>

  

" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />



![image](https://github.com/user-attachments/assets/1b8d0916-f448-4a6f-a355-9f1846b074cb)




<p>
Access the windows control panel. Inside the windows control panel, select programs and turn windows features on or off. You should see similar to the picture above. Under World Wide Web find Application Development Features, then under Application Development Features there will be CGI. Select CGI and continue with ok.

</p>
<p>

</p>
<br />

<p>


![image](https://github.com/user-attachments/assets/d24d5d7d-8877-45d7-9c17-85e16618f13e)


</p>
<p>
Going back to the unzipped OS-Ticket files, install the PHPManagerForIIS file. Next install the "rewrite_amd64_en-US". Both of these files must be installed to properly run the OS-Ticket application when we are finished. After installing these two, unzip the "php-7.3.8-nts-Win32-VC15-x86". Once this is done you must install the "VC_redist.x86" file followed by the "mysql-5.5.62-win32" file. (More information about the mysql file will be in the following picture.) When installing the mysql file, continue withe the typical install option. 
  
</p>
<br />




![image](https://github.com/user-attachments/assets/856ddfc0-25ef-4a69-9b86-d9df94f85a3b)



</p>
<p>

Open the mysql file after being installed and continue with the standard configuration. Next you will be shown the picture above. You must create a password and make sure they match each other. This passowrd is important and should not be messed up. Once everything is setup, run IIS as an administrator and select PHP Manager.



  ![image](https://github.com/user-attachments/assets/920fb724-d31d-4594-b129-a78fb2f97491)

</p>
<p>
 Register the new PHP version as the PHP CGI. After registering, reload IIS and make sure the process was completed correctly. If the proccess was done correctly, unzip the osTicket files within the osTicket installation files. Once the files are extracted you will see an upload file and a script file. Move the upload file into wwwroot. (The next picture will show the pathway to the www.root.) 

  ![image](https://github.com/user-attachments/assets/a50a2833-ca07-4677-b777-ce12685cf96b)

</p>
<br />


  
</p>
<br />
