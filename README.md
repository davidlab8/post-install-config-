R<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Install Configuration</h1>
This tutorial outlines the post-install configuration of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Configure osTicket, post-installation](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>Install Configuration Objectives</h2>

- Step 1. Configuring IIS on Windows using CGI, download install PHP Manager Rewrite mode, Create a directory (file) in Windows C drive 
          install PHP 7.38 file extract this file into empty file on C-drive naming it PHP.

- Step 2. Download install VC Redit & My SQL, Configure IIS to register new PHP version. Install Osticket extract copy (Upload folder) 
          into www.root name file ( osticket )
  
- Step 3. On IIS manager default Osticket (refresh page), browse 80 Osticket installer menu should appear,
          Enable following files on PHP manager ( php.imap, php.intl, php.opcache ),
          Inside ( Include folder ) rename file ( ost-sampleconfig to ost-config ) Assign permission to ost-config file allowing 
          everybody to use.

- Step 4. Osticket installer menu fill out the following. help desk name, email admin name, email username, and password
          Install Heidi SQL create database user, password
          fillout rest of the Osticket menu install software, Log in using admin username and password. 

     
<h2>Configuration Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 1. Installing IIS in windows with CGI in start menu type (control panel) go to programs, turn windows features on/off, 
        (windows features menu) go to Internet informaation Service, World wide web services, inside Application development features 
        (check box CGI) make sure (common HTTP features) and (IIS management console) are selected as well.
        
Install PHP manager and Rewrite mode from simple list lab instructions
(https://docs.google.com/document/d/12QH7yrsaiUfYNOgZK7KgTSZQSJ-HYTSVcGFildWMRig/edit#bookmark=id.cajb4ktub1km)</p>

Create a directory (file) inside Windows C drive go to file folder, this pc, Windows C drive, create new file (name file PHP) 
download PHP 7.38 (right click) extract, browse look for empty PHP folder inside C drive, extract will put files inside PHP 

Download Vc Redist and My Sql from simple list on my sql menu click typical install, standard config, name Root Pass make one up.

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Step 2. Register new PHP version to PHP manager go to start type iis (run as admin) PHP manager, register new PHP version,
        Browse, look for PHP CGI under PHP folder located inside Windows C-drive.

install Osticket inside file there is (Upload folder) open file folder, this pc, win c, inetub, www.root drag (upload) folder inside www.root folder name folder (Osticket).

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Step 3. Go to IIS manager page sites> defaualt> Osticket folder, (action manage folder), Browse 80 (Osticket installer page appears)
Enable files for Osticket IIS manager menu go to PHP manager, enable or disable, enable following: php_imap, php_intl, php_opchache
(refresh Osticket installer)


Rename file ossample.config to ost-config file is on windows c drive inside osticket upload folder.
  <p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>Step 4. 


