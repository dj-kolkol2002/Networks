# Networks - Cisco Packet Tracer Labs 🖧

![Cisco](https://img.shields.io/badge/Cisco-Routing_&_Switching-1BA0D7?style=flat-square&logo=cisco)
![Status: Done](https://img.shields.io/badge/Status-Done-green?style=flat-square)

**Practical implementations and configurations of network services in a simulation environment.**
This project is a collection of network labs created in Cisco Packet Tracer, solving common routing and security problems. The repository is intended for computer network enthusiasts and people studying for certifications such as CCNA, serving as a base of ready-made topologies for analysis, modification, and testing.

## 🛠️ Technologies
* Cisco Packet Tracer
* Cisco IOS
* Network protocols (IPv4/IPv6, OSPF, NAT, DHCP, ACL)

## ✨ Features
Based on the provided files, the project offers ready-made test environments for the following functionalities:
* **Traffic filtering:** Configuration of standard and extended Access Control Lists (`ACL.pkt`, `ACL extended.pkt`).
* **Dynamic routing:** Implementation of interior routing based on the OSPF protocol in a single area (`single-area ospf.pkt`).
* **Static routing:** Deployment of static routes (including default routes) for IPv4 and IPv6 protocols (`defaultroute.pkt`, `ipv4 i ipv6 route.pkt`).
* **Network services:** Automatic IP address allocation via DHCP server (`dhcp.pkt`) and Network Address Translation for external access (`nat.pkt`).

## ⚙️ The Process
Each lab in the repository represents an isolated environment solving a specific architectural problem. 
* The architecture is based on classic topologies using Layer 2 and Layer 3 routers and switches from the Cisco device family.
* The deployment process for each lab started with designing a logical connection topology and addressing plan (subnetting), then transitioned to the precise configuration of network mechanisms and services from the command-line interface (CLI).

## 📊 Proof of Concept / Testing
* _(Space for your screenshots - insert images showing e.g., connection topologies arranged in Packet Tracer here)_
* _(Optional: CLI logs showing a successful `ping` between end networks or screenshots of the `show ip route` command)_

## 💡 What I Learned
* In-depth understanding of the mechanisms and logic behind infrastructure services such as DHCP and NAT.
* Ability to implement stable static and dynamic routing (OSPF) for both addressing standards (IPv4 and IPv6).
* Practical ability to secure and control network traffic using dedicated ACL rules.

## 🚀 What can be improved
* Combining separate configuration files into one comprehensive corporate topology.
* Expanding the OSPF routing configuration to a Multi-Area architecture.
* Implementation of redundancy protocols, such as HSRP (First Hop Redundancy Protocol) or EtherChannel.

## How to run the Project
Step-by-step instructions on how to test the labs on your local machine:
* Clone the repository to your local drive using the command: `git clone https://github.com/dj-kolkol2002/Networks.git`
* Make sure you have **Cisco Packet Tracer** installed.
* Open Packet Tracer, then navigate to `File -> Open` and select a `.pkt` file of your choice (e.g., `nat.pkt`).
* Click on specific devices (routers/switches) and go to the **CLI** tab to freely analyze the configuration using the `show running-config` command or verify connectivity with the `ping` tool.
