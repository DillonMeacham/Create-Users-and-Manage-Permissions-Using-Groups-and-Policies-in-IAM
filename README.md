<h1>Create Users and Manage Permissions Using Groups and Policies in IAM</h1>

<h2>Description</h2>
Alfredo of Alfredo's Pizza has hired me as a security engineer for his web app that allows customers to order pizzas online. He's hired four new employees for the development team needs help giving this team the proper access permissions. In order to provide access and ensure the proper security measures are in place, I will use AWS Identity and Access Management (IAM) to group users and assign permissions for the developer group using policies.<br />


<h2>Environments Used </h2>

- <b>AWS Identity and Access Management (IAM)</b>

<h2>Project walk-through:</h2>

<p align="center">
Create new policy by importing the Lambda Full Access managed policy: <br/>
<img src="https://imgur.com/nuk9189.png" height="80%" width="80%" />
<br />
<br />
Review policy settings and confirm:  <br/>
<img src="https://imgur.com/kdzFMwl.png" height="80%" width="80%"
<br />
<br />
Create user group and attach managed policy to group: <br/>
<img src="https://imgur.com/WdlZB8S.png" height="80%" width="80%"
<br />
<br />
<img src="https://imgur.com/P4g9Yb2.png" height="80%" width="80%"
<br />
<br />
Add users to Developer user group:  <br/>
<img src="https://imgur.com/d7f3LJc.png" height="80%" width="80%"
<br />
<br />
