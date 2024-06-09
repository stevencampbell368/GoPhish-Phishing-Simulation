<h1>GoPhish Phishing Simulation</h1>

 </h2>

<h2>Description</h2>
In this task, I designed and executed a phishing campaign to gain insight into the methods employed by cybercriminals. Utilising GoPhish, I set up simulated phishing emails to evaluate how effectively people could detect and respond to them.
<br />


<h2>Part 1: Setting Up the Environment</h2>
<br />


<p>1. The first step involved logging into my Ubuntu Virtual Machine using VirtualBox. This provided the necessary environment for setting up GoPhish.</p>

<p>2. Next, I downloaded the latest version of Gophish from the official GitHub repository and then confirmed the installation of the Gophish package in my directory using the ls command.</p>

<p>3. After confirming the package, I installed the unzip utility and unzipped the GoPhish package to access its contents.</p>

<p>4. Using Nano, I edited the config.json file to set the listening URL, which is crucial for configuring the Gophish server.</p>

<p>5. I changed the permissions to make the file readable, writable, and executable by all users, ensuring it could be properly executed.</p>

<p>6. Ran the Gophish executable file to start the application.</p>

<p>7. Moved into the Gophish directory to ensure all commands were executed in the correct location.</p>

<p>8. Finally, I started the Gophish server to begin the setup.</p>


<p align="center">
<img src="https://imgur.com/PrC1z8D.png" height="65%" width="65%" alt=""/>
</p>


<b>Step 2: Accessing the GoPhish Web Interface</b>

<p>1. I opened the web browser and entered my unique server IP address to access the GoPhish web interface.</p>

<p>2. Created a new admin account and logged into the GoPhish dashboard to begin configuring the phishing campaign.</p>

<p align="center">
<img src="https://imgur.com/Q0Tex1H.png" height="65%" width="65%" alt=""/>
</p>


<h2>Part 2: Configuring the Phishing Campaign</h2>
<br />

<b>Step 1: Configuring SMTP Settings for GoPhish</b>

<p>1. I navigated to the “Settings” tab and selected “Sending Profiles” to begin configuring the email settings</p>
<p>2. Clicked on “Add Sending Profile” and provided the details for my open-source SMTP server:</p>
</p>•SMTP Server: The IP address or hostname of the SMTP server.</p>
</p>•SMTP Port: The SMTP port used by the server (e.g., 25, 587).</p>
</p>•From Address: My personal Gmail address.</p>
</p>•From Name: The name associated with the sender’s email address.</p>
</p>•SMTP Username: Provided if the SMTP server requires authentication.</p>
</p>•SMTP Password: Created a Google app password.</p>
</p>•Use TLS/SSL: Enabled this option for a secure connection.</p>
<p>3. I sent a test email to ensure the settings were configured correctly and functioning as expected.</p>

<p align="center">
<img src="https://imgur.com/kiCBUz7.png" height="65%" width="65%" alt=""/>
</p>


<b>Step 2: Creating an Email Template</b>

<p>1. The "Template" is the content of the emails sent to targets.</p>
 
<p>2. Utilised an example HTML Microsoft template to create a realistic phishing email.</p>

<p align="center">
<img src="https://imgur.com/srHkWjQ.png" height="65%" width="65%" alt=""/>
</p>



<b>Step 3: Setting Up the Landing Page</b>

<p>1. Created the HTML page that recipients are forwarded to when they click the URL in the email template.</p>

<p>2. Utilised an example HTML Microsoft template for the landing page.</p>

<p>3. Enabled the "Capturing Credentials" option to capture credentials entered by the user.</p>

<p>4. Enabled the "Redirecting Users" option so that after entering credentials, users are redirected to the official Microsoft URL, which helps prevent users from becoming suspicious after entering their credentials.</p>

<p align="center">
<img src="https://imgur.com/WPSju6A.png" height="65%" width="65%" alt=""/>
</p>






<b>Step 4: Adding Users and Groups</b>

<p>1. Manually enter a user, filling in the text boxes for "First Name," "Last Name," "Email," and "Position," and click the "Add" button."</p>

<p align="center">
<img src="https://imgur.com/iJCyiSJ.png" height="65%" width="65%" alt=""/>
</p>


<b>Step 5: Launching the Campaign</b>

<p>1. Configured and launched the campaign.</p>
<p>2. Viewed the campaign results to analyse the effectiveness and gather insights on the phishing detection and response capabilities of the targets.</p>

<p align="center">
<img src="https://imgur.com/iJCyiSJ.png" height="65%" width="65%" alt=""/>
</p>






<p>In this project, I explored phishing simulations with GoPhish. It provided valuable insights into cybercriminal tactics and improved my understanding of user reactions to phishing attempts. From setup to analysis, it's been a rewarding experience that's enhanced my cybersecurity skills.</p>



<h2>Languages Used</h2>

- <b>HTML:</b> Used for creating email templates and landing pages. 
- <b>Bash: </b> Used for running commands and managing files on the Kali Linux VM.

<h2>Environments Used </h2>

- <b>GoPhish:</b> Phishing simulation tool used to design and execute the phishing campaign.
- <b>VirtualBox:</b> Virtualization software for running the Kali Linux VM.


<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
