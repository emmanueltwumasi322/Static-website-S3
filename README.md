<h1>Hosting a Static Website on Amazon S3 + CloudFront Distribution</h1>

<h2>Description</h2>
This project demonstrates how I deployed a simple static website using Amazon S3. It highlights the fundamentals of cloud hosting, S3 bucket configuration, CloudFront and static site deployment.<br />


<h2>Technologies Used</h2>

- <b>Amazon S3</b> 
- <b>AWS Management Console</b>
- <b>HTML</b>
- <b>CloudFront</b>
    
<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

<h2>Walk-through:</h2>

<p align="center">
Step 1: Created an S3 Bucket and uploaded static files.<br/>
<img src="https://i.imgur.com/reF4SgV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 2: Enabled static website and unchecked "block public access".<br/>
<img src="https://i.imgur.com/AOMoQQN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 3: To allow the images and other static assets in the S3 bucket to be publicly viewable, I updated the object ownership settings:
	1.	Navigate to Permissions → Object Ownership, and enable ACLs.
	2.	Select all uploaded files, choose Actions → Make public using ACL. This ensures that all objects can be accessed publicly when the static website loads. <br/>
<img src="https://i.imgur.com/6wMpI5K.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 4: To improve speed and security, I added a CloudFront Distribution service in front of the static website. I chose S3 as the origin type and used the CloudFront public URL as the main link to the website.
<img src="https://i.imgur.com/aSpiy1s.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Step 5: Search website URL.  <br/>
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
