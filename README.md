<h1>Hosting a Static Website on S3</h1>

<h2>Description</h2>
This project demonstrates how I deployed a simple static website using Amazon S3. It highlights the fundamentals of cloud hosting, S3 bucket configuration, and static site deployment.
<br />


<h2>Technologies Used</h2>

- <b>Amazon S3</b> 
- <b>AWS Management Console</b>
- <b>HTML</b> 

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Walk-through:</h2>

<p align="center">
Create an S3 Bucket and upload files: <br/>
<img src="https://i.imgur.com/reF4SgV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enable static website and uncheck "block public access":  <br/>
<img src="https://i.imgur.com/AOMoQQN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
To allow the images and other static assets in the S3 bucket to be publicly viewable, I updated the object ownership settings:
	1.	Navigate to Permissions → Object Ownership, and enable ACLs.
	2.	Select all uploaded files, choose Actions → Make public using ACL.

This ensures that all objects can be accessed publicly when the static website loads. <br/>
<img src="https://i.imgur.com/6wMpI5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Search website URL:  <br/>
<img src="https://i.imgur.com/h5qRlFF.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
