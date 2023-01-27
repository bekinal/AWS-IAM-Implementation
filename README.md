<h1>AWS IAM Implementation</h1>

<h2>Description</h2>
Project consists of implementing IAM features for AWS accounts to provide a better understanding of the IAM concept.
<br />


<h2>Utilities Used</h2>

- <b>Amazon Web Services</b>

<h2>Creating AWS account groups:</h2>
IAM is typed in the AWS search bar to navigate to its dashboard:<br/>
<img src="https://imagizer.imageshack.com/img923/2602/dd1ucV.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Under IAM resources, User Groups is selected:<br/>
<img src="https://imagizer.imageshack.com/img924/2263/eVtERx.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Create Group is selected:<br/>
<img src="https://imagizer.imageshack.com/img922/5388/WmqWRH.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
A user group named Developers is created:<br/>
<img src="https://imagizer.imageshack.com/img922/4106/EhVACs.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
In the search bar, AdministratorAccess is entered. The policy is selected and Create Group is clicked to proceed. This gives our Developer user admin access of our root AWS profile:<br/>
<img src="https://imagizer.imageshack.com/img923/1603/cvAcK5.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<h2>Creating AWS Account Users:</h2>
Under Access management, Users is selected:<br/>
<img src="https://imagizer.imageshack.com/img923/9225/HclWyd.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The first user name is Emily. A password is enabled that allows this user to access the AWS Management Console:<br/>
<img src="https://imagizer.imageshack.com/img924/3940/qULtjH.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Under the Add user to group box, Developers is selected. This user will have admin privileges:<br/>
<img src="https://imagizer.imageshack.com/img924/8449/Ebmks8.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
The tag is skipped, and the user account is reviewed:<br/>
<img src="https://imagizer.imageshack.com/img922/8324/j17VhW.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Download .csv is clicked to downloaod the user's login and URL credentials. This window is then closed:<br/>
<img src="https://imagizer.imageshack.com/img924/1225/YuM3PG.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Emily is logged in as an IAM user. Under Emily, another user named Alex is created. alex is then added to the QA group:<br/>
<img src="https://imagizer.imageshack.com/img923/9185/VlI2t6.png" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Alex is logged in and is denied privileges when trying to create another user:<br/>
<img src="https://imagizer.imageshack.com/img922/1436/DVi2OI.png" width="80%" alt="Disk Sanitization Steps"/>
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
