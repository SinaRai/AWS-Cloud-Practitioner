# **Walkthrough: Securely Accessing Private Instances Using a Bastion Host**

Before starting, let's understand the concept of a Bastion Host and why it's necessary to access instances in a private subnet.

### **Bastion Host**

A **bastion host** is a server whose purpose is to provide access to a private network from an external network, such as the Internet. Its primary function is to enable secure and controlled access to private instances that are usually not directly reachable from the public internet. The bastion host is deployed in a public subnet, directly connected to the internet, and accessible via SSH. Furthermore, it allows SSH access to instances in a private subnet, enabling secure internet access from within the private network using SSH Agent Forwarding.

The bastion host acts as a secure gateway, enabling users to securely connect to private instances within the VPC while maintaining the integrity and confidentiality of the network environment. This setup enhances security by limiting exposure to potential threats and providing a centralized point for monitoring and managing access.

## **Solution Architecture**

<p align="center">
    <img src="Lab/Images/Architecture.jpg">
</p>

The diagram illustrates the configuration of a bastion host within your AWS VPC cloud environment.
