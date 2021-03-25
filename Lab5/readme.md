# Executive Summary
The purpose of this lab is to identify network compnenets, topologies, and understand the role of the NSA in cybersecurity. Additionally, encyrption and approaches to cybersecurity to reduce threats will be reviewed. 
## Lucidchart
The purpose of Lucidchart is to utilize a visual workspace to visualize process, technical systems, etc. Using the resources avaiable on the site, it is very simple to create a diagram for whatever needs a project may have. It is a great way to make sure that everyone stays on the same page regarding when and how things should be done, programmed, tested, etc. 
## Introduction to Networking
### Data Transmission
There are several important terms that fall under the umbrella of data transmission.
1. Packet: The unit of data that is transmittied via the internet.
2. IP Address: The unique identifying number that every device has.
3. DNS: A.k.a the domain name server is a directory of IP address common names. For example 54.239.26.214 might be the IP address of amazon.com.
4. Packet-Switching: Technology that allows packets of data to be routed based on destination address. 
5. Protocol: The set of rules to allow devices to communicate.

All of these things are related because, for any one piece of data to be transmitted, it must follow protocol to originate at a specific IP address as a packet, then access the DNS so that the IP address of the recieving destination is located, and finally use paclet switching to send and reassemble the original packet to the reciever can access it. 
### Network Hardware 
There are three major pieces of networking hardware to be concerned about: routers, switches, and hubs.
A hub does not filter any data it recieves and sends it to every device connected to its port. A switch is similar but it is able to learn the physical destination of any connected devices and is therefore able to send data to a specific device connected to the port so it is more secure than a hub. This reduces unnecessary traffic on the network. However, hubs and switches can only be used to send data within their local network, to send data over the internet the device needs to be able to read IP addresses. A router is able to read IP addresses to determine whether a data packet is meant for its own network or for another network. If it was meant for another network the router then sends that packet to another network or accept the packet if it was in fact meant for its network.
### Network Topologies
A single point of failure is when the central hub or switch of the topology fails and causes the entire network to go down. This occurs in the star, bus and ring topologies. 

Infrastructure topology is a wireless topology that uses a combination of wired and wireless devices. It functions similar to a star topology but contains wireless access points to allow for wirless devices to connect to the wired network. 
Wireless mesh topology is when each computer on the network is connected to a wireless access point which then connects with other WAPs to eventually connect to the modem and the internet. The advantage of this is that even if a few WAPs go down, the devices can still communicate with the other devices and get the data to its destination using a different path.

The wireless mesh topology is the most beneficial of the toplogies because it removes the failure that can occur when wired connections are involved such as in the infrastructure toplogy. If a part of the wired network failed then the wireless part of it would not be able to connect. 
### Network Design
The topology displayed by the diagram is a wireless mesh topology consisting of two computers and a printer each connected to a wireless access point which then connect to a router to create the wireless network. 
### NSA/CSS
The NSA plays a large role in cybersecurity for the U.S. They provide education, products and services, technical guidance and advisories, and threat intelligence and assesments  that are available to whoever may need it. They provide support, knowledge and assistance to the military cryptology community through the CSS. 
## Cybersecurity and Encryption
### Information Systems Security
