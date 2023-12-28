<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Install Configuration</h1>
This tutorial is a step by step guide on the install configuration of the Osticket help desk ticketing system.


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Step by Step Install Configuration</h2>

- Step 1. On Azure create Resource Group and VM1 (Windows 10), connect VM1 to remote desktop.
  - Configure IIS on Windows using CGI.
  - download install PHP Manager and Rewrite mode from simple list provided by Course careers.
     https://drive.google.com/drive/u/0/folders/1APMfNyfNzcxZC6EzdaNfdZsUwxWYChf6)

- Step 2. Create a directory (file) in Windows C-drive 
          name file PHP, download and install PHP 7.38 extract this file into empty PHP file.
  - Download, install VC Redit & My SQL,
  - Configure IIS to register new PHP version.
 
 - Step 3. Install Osticket, inside file drag (Upload folder) to www.root name file ( osticket )
   - (IIS manager menu) Osticket (refresh page), browse 80 (Osticket installer menu should appear)
   - Enable following files on PHP manager ( php.imap, php.intl, php.opcache ).

- Step 4. Inside ( Include folder ) rename file ( ost-sampleconfig to ost-config ) Assign permission to ost-config file allowing 
          everybody to use.
   - Osticket installer menu fill out the following. help desk name, email admin name, email username, and password
   
   - Install Heidi SQL create database, user and password.
          fill out rest of the Osticket menu install software.

- Step 5. Clean up erase Setup folder in Root file, set permission to read only and log in help desk using admin user name and password.
(http://localhost/osTicket/scp/login.php)     
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
   - Step 1.  On Azure create Resource Group and VM1 (Windows 10), connect VM1 to remote desktop  
  
  - Installing IIS in windows with CGI in start menu type (control panel) go to programs, turn windows features on/off, 
       (windows features menu) go to Internet information Service, World wide web services, inside Application development features 
        (check box CGI) make sure (common HTTP features) and (IIS management console) are selected as well.
        
  - Install PHP manager and Rewrite mode from simple list lab instructions

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
- Step 2. Create a directory (file) inside Windows C-drive go to file folder, this pc, Windows C-drive, create new file (name file PHP) 
download PHP 7.38 (right click) extract, browse, look for empty PHP folder inside C-drive, extract files will start going inside PHP folder 

 - Download Vc Redist and My Sql from simple list
on My Sql menu click typical install, standard config, name Root Password Password1 as (example).  
  
  - Register new PHP version to PHP manager go to start type iis (run as admin) PHP manager, register new PHP version,
        Browse, look for PHP CGI under PHP folder located inside Windows C-drive.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
  install Osticket inside file there is (Upload folder) open file folder, this pc, win c, inetub, www.root drag (upload) folder inside www.root folder name folder (Osticket)  
  
  
  Step 3. Go to IIS manager page sites> defaualt> Osticket folder, (action manage folder), Browse 80 (Osticket installer page appears)
Enable files for Osticket IIS manager menu go to PHP manager, enable or disable, enable following: php_imap, php_intl, php_opchache
(refresh Osticket installer)


Rename file ossample.config to ost-config file is on windows c drive inside osticket upload folder.
  <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Step 4. Assign permission on ost-config file (right click) ost-config file property, security, advanced, disable inheritance,
remove all inherited permission from object, add (permission) select principal, (type) everyone, check names, (basic permission) 
full control, apply (now everyone can use ost-config file )

Osticket menu fill out the following: help desk name and email, Admin first, last name, email, username, password. 

Set-up database for Osticket download and install Heidi Sql from (simple list) (Heidi Sql menu) new, settings username root, 
make up password, open

Creating database (Heidi Sql menu) (right click) unamed, create new, database, (name it) osticket, install
fill out rest of the osticket installer menu mysql name: root, mysql password:, install now (osticket program succesfully installed) 

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Step 5. Clean up erase setup folder in root file (file folder) thispc, win-c, instpub, www.root, inside (osticket folder) 
erase setup folder.

Set permissions for read-only go to (include folder), ost-config file, (right click), properties, security, advanced, (click) everyone
edit, leave Read and Read & execute boxes checked only, apply

Log in help desk osticket 
(http://localhost/osTicket/scp/login.php)http://localhost/osTicket/scp/login.php
type admin username and password.

