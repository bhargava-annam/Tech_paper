# Firewalls

>## Introduction

A firewall is a software program or a piece of hardware that helps to screen out hackers, viruses that try to reach your computer over the [Internet](https://en.wikipedia.org/wiki/Internet). Firewall monitors and filters incoming and outgoing network traffic similar to the previously defined security policies of an organization. A firewall is an obstacle between a private internal network and the public Internet. The main aim of a firewall is to allow non-threatening traffic in and to keep unsafe traffic out.

![](https://cdn.hswstatic.com/gif/firewall.gif "Firewall")

There are two types of firewalls.
1) Software Firewall
    * A software Firewall is a program that is installed on your computer.
1) Hardware Firewall
    * A hardware firewall is a device that is placed in between your network and untrusted Internet.

>## Working of Firewall

The basic task of the Firewall is to regulate the flow of traffic in between the computer networks of different trust levels. All incoming and outgoing messages are passed through Firewall. It checks whether these satisfy the security criteria or not. If they satisfy the security criteria then they are allowed otherwise they are blocked.

   <img src="https://learn.g2.com/hs-fs/hubfs/firewall3.gif?width=600&name=firewall3.gif" width=auto height="250">

Internet is an untrusted network of connected computers. When we try to connect/run a website on google, the request goes to the internet and searches for the website in the group of connected computers and projects it on our personal computer. In this process, hackers/un-authorized persons get access to these Internet connections and try to steal our sensitive information but Firewalls protect you from these attacks with the help of various techniques.

>## Techniques 

There are several different ways security firewalls can monitor and regulate network traffic.
* **Packet filtering** 

      Packets are small quantities of information. If a firewall uses packet filtering, it runs a group of checks against packets attempting to reach the network. These filters block packets that correspond to certain threats listed and allow others to access their intended destination. 


* **Proxy service**

      Instead of serving as a filtration system that data passes through, proxy servers function as go-betweens. They avoid direct communications between the client system and the incoming packets, securing the network location from unknown malicious users, by effectively creating a copy of the system behind the firewall. These firewalls are extremely stable but have some drawbacks. They function more slowly than other firewall types and are therefore constrained in terms of the kinds of applications that they can serve.


* **Stateful inspection**

      Where the packet headers are checked by static filtering, host-based firewalls analyze a variety of elements of each data packet and compare them to a trusted knowledge database. These elements include IP addresses, ports, and applications from the source and destination. To be allowed through the firewall, incoming data packets are required to adequately match the trusted information.  
  
> ## Limitations

Some of the limitations of the firewalls are as follows

* Malicious insiders
* Connections that circumvent it
* Completely new threats
* Some viruses
* The administrator that does not correctly set it up

>## Reference

*  (*Vedio series on Firewalls*)
 *https://www.youtube.com/watch?v=eO6QKDL3p1I&list=PLBbU9-SUUCwV7Dpk7GI8QDLu3w54TNAA6*
* *https://www.checkpoint.com/cyber-hub/network-security/what-is-firewall/*


* (*Limitations*)*https://www2.dmst.aueb.gr/dds/secimp/fv/lim.html*
