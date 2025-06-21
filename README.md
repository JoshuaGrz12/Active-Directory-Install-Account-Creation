# Active-Directory-Installation
<h2>Description</h2>
Using Windows server 2016 to install active directory
<br />


<h2>Environments Used </h2>

- <b>Oracle Virtual box</b> 

<h2>Project walk-through:</h2>

<p align="center">
The first thing I will be doing is changing the computer name to make it easier to identify and orgainze: <br/>
<img src="https://i.imgur.com/gZSHVKG.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Going into server manager I will choosing the role based option to install to make it a domain conroller to add things to it in the future:  <br/>
<img src="https://i.imgur.com/fTBQIRv.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Simply choosing I want the Active Directory Domain Services wanting to install the features with it
: <br/>
<img src="https://i.imgur.com/diS9HrM.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
I will then promote this to a domain controller then be choosing to add a new forest since I don't hold any domain and will have to create one
:  <br/>
<img src="https://i.imgur.com/YeFBYdQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
 
<h2>Conclusion:</h2>
After the last step finishes the installation will take place then this domain controller will serve as the hub for subsequent lab projects, including joining client machines to the domain, creating user and group accounts, implementing Organizational Units (OUs), and deploying Group Policy Objects (GPOs) to manage user environments and enforce security standards.
