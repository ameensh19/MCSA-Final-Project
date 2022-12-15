# MCSA-Final-Project
Creating and managing a Microsoft environment- Server management

In this project we will discuss the Microsoft environment- Server management, and the local area network, in order to reduce the risk exposure for any organizations using a range of managerial, legal, technological, process and social controls.

The LAN presented in this work includes 3 main elements:
1.	DC- a Windows server with domain controller- Active Directory, DHCP and DNS services installed on it.
2.	SRV1- a Windows server functioning as a router with routing and NAT services.
3.	WIN10- a Windows station operating as the client. 

We will be starting our work by preparing our Lab and install our DC server, WIN10 and SRV1 on the VMware workstation; get the system updated and turn off all the Firewall’s to make the work less complex; However, we will define the names of each devices as we can see in the diagram attached below. 

Moreover, we will Check and make sure there is a successful connection between all the devices by using the PING command and ipconfig /all.
WIN10 will get an automatic assignation of an IP address, later on, which will be set to obtain its IP address automatically as a result of communication with the DHCP servers of DC.

Also we will Check the ability to access the internet in DC and WIN10 due to SRV1’s routing services and more.

The following diagram presents the tropology of the network analyzed in this project:

<img width="456" alt="image" src="https://user-images.githubusercontent.com/119690999/207849767-aef37fac-9120-48e1-b465-7189a31a258a.png">

The Switch will not be discussed though it’s represented in the diagram to show a reliable depiction of the physical topology of the LAN. 

Instead of that; All the devices will be connected to VMnet9 in the VMware Network Connection.
