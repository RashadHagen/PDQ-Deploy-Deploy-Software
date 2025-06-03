<h1>PDQ Deploy – Deploy Software</h1>


<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Description</h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
This project goes over how to deploy software using PDQ Deploy.  PDQ Deploy is a software deployment tool that automates the process of installing, uninstalling, repairing, or upgrading software on multiple Windows devices across a network. It simplifies software management by offering pre-built packages for common applications, allows for custom package creation, and enables scheduling and automation of deployment tasks.
</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;">
⏹️ Utilities Used</h2>
  
<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
 - <b>PDQ Deploy</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
⏹️ Environments Used </h2>

<p style="font-family: Georgia, serif; font-size: 16px; margin-top: 12px; margin-bottom: 12px;">
 
- <b>Windows Server 2016</b>



<h2 style="font-family: Arial, sans-serif; font-size: 20px; font-weight: bold; margin-top: 24px; margin-bottom: 12px;"> 
<h2>
⏹️ Project Walk-Through:</h2>
 <br/>

<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Package Library to see the applications you can install & to install them  (left-side column).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/fKq53Cv.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/Ih4Fqds.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/SXg7Nel.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Download the software you want to deploy (ex: Zoom).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/IQiCaxs.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/6qV3Gn4.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Packages (to see the applications you have downloaded).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/EQbINwG.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/KikDew8.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/g7Isrf9.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/NYmqUmX.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Right-Click: Zoom.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/UgEvbU6.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Deploy Once.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/Hpu9cvX.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Choose Targets (middle-left box).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/MI7e2f5.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/lL9fWK5.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/8UlV7Al.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/R8MEfqV.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Put Mouse Over: Active Directory. Click: Computers.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/3lBZ53p.png" height="100%" width="100%" /></td>
    <td><img src=https://imgur.com/e75lpsx.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/BJzGk7F.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Select: The server  (OR)  computer you want as your Active Directory Target (ex: DCSERVER2016KIS).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/jqarAln.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: The single arrow pointing to the right to add a single server   (OR)   computer to the Targets box.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/KNjTdJG.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/29ZUDyb.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: OK.</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/tvKefFH.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/4YM36An.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />


<div style="text-align:center;">
  <span style="font-family: Arial, sans-serif; font-size: 16px;"><b>Click: Deploy Now (bottom-right).</b></span>  
<br/>

<table>
  <tr>
    <td><img src="https://imgur.com/0WmERdA.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/yieAAtN.png" height="100%" width="100%" /></td>
  </tr>
</table>

<table>
  <tr>
    <td><img src="https://imgur.com/jNMbC8r.png" height="100%" width="100%" /></td>
    <td><img src="https://imgur.com/0Kh196o.png" height="100%" width="100%" /></td>
  </tr>
</table>

<br /><br />
