<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Install Configuration</h1>
This tutorial is a step by step guide on the install configuration of the Osticket help desk ticketing system.


<h2>Video Demonstration</h2>

- ### [YouTube: OsTicket Introduction](https://www.youtube.com/watch?v=tj4al4ytCf0)
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

STEP 1.

![AE1C4177-518A-4E07-B5B0-B77FF385D2AE](https://github.com/davidlab8/post-install-config-/assets/154483052/4d9cbca4-89b0-47f7-94f5-96a133307c64)
 - Step 1.  On Azure create Resource Group and VM1 (Windows 10), connect VM1 to remote desktop

![7CD0DD1C-CDFA-42B8-A48C-64D215D71E61](https://github.com/davidlab8/post-install-config-/assets/154483052/e7445a8a-487e-42fc-80d2-4d0adf53fc7a)
 - Installing IIS in windows with CGI in start menu type (control panel) go to programs, turn windows features on/off

![B25156E8-27E7-492E-AB53-F5752811D9FC](https://github.com/davidlab8/post-install-config-/assets/154483052/5aca4b33-8166-4b54-886e-4b7c8130e47e)
 - (Windows Features Menu) go to Internet information Service, World wide web services, inside Application development features 
        (check box CGI) make sure (common HTTP features) and (IIS management console) are selected as well.

![11F16806-9FDB-4132-994F-C047F3EF7A3C](https://github.com/davidlab8/post-install-config-/assets/154483052/ad62cc66-e4a1-4bfc-9259-6c16e430b894)
  - Install PHP manager and Rewrite mode from simple list lab instructions

STEP 2.

![573CC34D-7BC3-4762-BBE3-D002DD94FD0B](https://github.com/davidlab8/post-install-config-/assets/154483052/95b36438-96c3-4f16-b33d-c3ff718cb27a)
- Step 2. Create a directory (file) inside Windows C-drive go to file folder, this pc, Windows C-drive, create new file (name file PHP) 
download PHP 7.38 (right click) extract, browse, look for empty PHP folder inside C-drive, extract files will start going inside PHP folder 

![7F4FC2B8-A6A5-47DA-9F17-15C6E3589306](https://github.com/davidlab8/post-install-config-/assets/154483052/608a2435-3819-435a-bba5-e8d75224e64b)
 - Download Vc Redist and My Sql from simple list
on My Sql menu click typical install, standard config, name Root Password Password1 as (example). 

![41E5C561-3733-49D3-89C8-D3B9ED170807](https://github.com/davidlab8/post-install-config-/assets/154483052/1885ec75-4358-4031-b1dd-13d7c9a61a57)
 - Register new PHP version to PHP manager go to start type IIS (run as admin) PHP manager, register new PHP version,

![7D40F681-FB8D-4A4D-A0BE-08B88F91710B](https://github.com/davidlab8/post-install-config-/assets/154483052/158aafef-90e5-4dee-8153-3dc810af8947)
 - Browse, look for PHP CGI under PHP folder located inside Windows C-drive.

STEP 3.

![IMG_1038](https://github.com/davidlab8/post-install-config-/assets/154483052/d72a00e7-3e1a-40c7-8eb6-5723bc95a39f)
 -Step 3. install Osticket inside file there is (Upload folder) open file folder, this pc, win c, inetub, www.root drag (upload) folder inside www.root folder name folder (Osticket)

 ![IMG_1039](https://github.com/davidlab8/post-install-config-/assets/154483052/3f6dcdc2-4f43-4f9d-b820-1263458af247) 
 - Start, IIS, IIS manager page sites> default> Osticket folder, (action manage folder), Browse 80 (Osticket installer page appears)

![IMG_1040 2](https://github.com/davidlab8/post-install-config-/assets/154483052/2ca1590e-70b4-4043-9e3e-ca07f2f7fc94)
 - Enable files for Osticket IIS manager menu go to PHP manager, enable or disable

![IMG_1041](https://github.com/davidlab8/post-install-config-/assets/154483052/2c941947-5e1a-402f-8cb9-7a0f3539dfb0)
 - Enable following: (right click) php_imap, php_intl, php_opchache (refresh Osticket installer)

STEP 4.

![IMG_1042](https://github.com/davidlab8/post-install-config-/assets/154483052/b0986ac9-9954-40ac-be24-769afe3b05ac)
-Step 4. Rename file ossample.config to ost-config file is on windows c-drive inside www.root, osticket, include folder.

![IMG_1043](https://github.com/davidlab8/post-install-config-/assets/154483052/3a16d361-7239-4236-8d56-a6abb03fe42d)
   - Assign permission on ost-config file (right click) ost-config file property, security, advanced, disable inheritance,
remove all inherited permission from object.

![IMG_1044](https://github.com/davidlab8/post-install-config-/assets/154483052/457c1809-6a26-4dad-9d72-33412e41ca8a)
   - Add (permission) select principal, (type) everyone, check names, (basic permission) 

![IMG_1045](https://github.com/davidlab8/post-install-config-/assets/154483052/44eb1f7d-036b-4e0c-80f4-dff7bb41ea13)
   - Full control, apply (now everyone can use ost-config file )


![IMG_1046](https://github.com/davidlab8/post-install-config-/assets/154483052/c0ee1f7b-daa8-446a-a3bd-4ba0831ee1c6)
 - Osticket installer, (click) continue, osticket menu fill out the following: help desk name and email, Admin first, last name, email, username, password. 
  
  ![IMG_1047](https://github.com/davidlab8/post-install-config-/assets/154483052/ee48cf31-6564-4a6a-bbe0-2485bcb8e1a4)
 - Set-up database for Osticket download and install Heidi Sql from (simple list) (Heidi Sql menu) new, settings username root, 
     password Password1 (example), open  
  
![IMG_1048](https://github.com/davidlab8/post-install-config-/assets/154483052/3d114068-7ad4-49f9-8840-173e0f599ebd)
  - Creating database (Heidi Sql menu) (right click) unamed, create new, database
  
![IMG_1049](https://github.com/davidlab8/post-install-config-/assets/154483052/89dad401-191e-4853-8650-1c8583d0406d)
  - Name it) osticket, install

![IMG_1050](https://github.com/davidlab8/post-install-config-/assets/154483052/bcc6b9e2-30fd-47e3-85aa-4b94999a5224)
  - Fill out rest of the osticket installer menu mysql name: root, mysql password: install now

![IMG_1051](https://github.com/davidlab8/post-install-config-/assets/154483052/b2de228c-0f67-4ff8-8184-7d87a18bb582)
  - Osticket program succesfully installed.

STEP 5.

![IMG_1052](https://github.com/davidlab8/post-install-config-/assets/154483052/f27ff967-ee9d-4b29-bfa5-feea903466c0)
  -Step 5. Clean up erase setup folder in root file (file folder) thispc, win-c, instpub, www.root, inside (osticket folder) 
erase setup folder.

![IMG_1053](https://github.com/davidlab8/post-install-config-/assets/154483052/17b21ac5-7b99-4403-b30a-e16a24f7760f)
 - Set permissions for read-only (include folder) this pc, win-c, inetpub, www.root, osticket, (include folder) ost-config file, (right click), properties, security, advanced, (click) everyone edit


![IMG_1054](https://github.com/davidlab8/post-install-config-/assets/154483052/f75a16eb-8143-47ed-9eef-6418436b0c16)
 - leave Read and Read & execute boxes checked only, apply

![IMG_1055](https://github.com/davidlab8/post-install-config-/assets/154483052/f95aca5b-c718-4230-a01c-e31712e0f3a2)
 - Log in help desk osticket 
(http://localhost/osTicket/scp/login.php)http://localhost/osTicket/scp/login.php
type admin username and password.

![IMG_1056](https://github.com/davidlab8/post-install-config-/assets/154483052/d33478be-c050-4818-92d5-ba9dc1ac0c03)
- Now your inside Osticket Menu as Admin. 


