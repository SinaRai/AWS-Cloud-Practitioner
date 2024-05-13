<h1><Strong>Walkthrough: Securely Accessing Private Using a Bastion Host</Strong></h1>
<br>
<p>Before starting, let's have the concept of a Bastion Host and why it's necessary to access instances in a private subnet. <br>
<h3><strong> Bastion Host <strong></h3>
   A bastion host is a server whose purpose is to provide access to a private network from an external network, such as the Internet.Its primary function is to enable secure and controlled access to private instances that are usually not directly reachable from the public internet.<br>
   
   Bastion Host acts as a secure gateway, enabling users to securely connect to private instances within the VPC while maintaining the integrity and confidentiality of the network environment.This setup enhances security by limiting exposure to potential threats and providing a centralized point for monitoring and managing access.
</p>
<br>
<h2><strong> Solution Architecture <strong></h2>
<p align="center">
    <img src="Assets/Accessing_PrivateInstances.jpg" alt="Solution Architecture"> 
</p>