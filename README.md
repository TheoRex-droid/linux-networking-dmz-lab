# Linux Networking DMZ Lab 

## Overview
This project demonstrates a segmented Linux network built in VirtualBox using MiniOS virtual machines. 

The environment simulated an enterprise network architecture with LAN and DMZ connected through a Linux gateway router. 

## Network Topology

     Internet
        |
     Gateway VM
     /        \
192.168.10.0   10.0.50.0
    LAN           DMZ
     |           /  \
LAN Client   Web Server SSH Server    

## Technologies Used 

Linux
VirtualBox
IP Routing
Static IP Configuration
Network Segmentation
SSH

## Key Commands Used

Assign IP address
sudo ip addr add 10.0.50.20/24 dev eth0
Enabel interface
sudo ip link set eth0 up
Add default route
sudo ip route add default via 10.0.50.1
Verifying networking 
ip a 
ip route 

## Skills Demonstrated

Linux networking
Virtual Machine networking 
Gateway routing configuration 
DMZ architecture
Networking troubleshooting 
