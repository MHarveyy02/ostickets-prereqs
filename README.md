<p align="center">
<img src="https://i.imgur.com/Clzj7Xs.png" alt="osTicket logo"/>
</p>

<h1>osTicket - Prerequisites and Installation</h1>
This tutorial outlines the prerequisites and installation of the open-source help desk ticketing system osTicket.<br />


<h2>Video Demonstration</h2>

- ### [YouTube: How To Install osTicket with Prerequisites](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Internet Information Services (IIS)

<h2>Operating Systems Used </h2>

- Windows 10</b> (21H2)

<h2>List of Prerequisites</h2>

- Item 1
- Item 2
- Item 3
- Item 4
- Item 5

<h2>Installation Steps</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Before installing osTicket, ensure your server meets the necessary requirements. You'll need a web server (such as Apache or Nginx), PHP, a database server (MySQL or MariaDB), and PHP extensions like GD, IMAP, and XML. Make sure your server's software versions are compatible with osTicket's requirements.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Choose a web server (e.g., Apache or Nginx) and configure it to serve osTicket. Create a virtual host or site configuration, pointing to the osTicket installation directory. Ensure that the web server has the necessary permissions to access and modify files in the osTicket directory.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Adjust PHP settings according to osTicket's requirements. Set the timezone, increase memory_limit, and enable necessary extensions like GD, IMAP, and XML. Verify that your PHP version is compatible with osTicket. You can typically find recommended PHP settings in the osTicket documentation.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Create a database and a database user for osTicket. Use MySQL or MariaDB, and make sure the database user has the required privileges. During the osTicket installation process, you will need to provide these database details. Keep the database credentials secure, as they will be used for establishing a connection between osTicket and the database.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Download the latest version of osTicket from the official website. Extract the files to your web server directory. Open a web browser and navigate to the osTicket installation wizard by accessing the installation URL. Follow the on-screen instructions, providing the necessary information such as database details, admin credentials, and system settings. After completing the installation, remove the setup directory for security reasons.
</p>
<br />
