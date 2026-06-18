# Enterprise Campus Network Design

A complete enterprise network infrastructure designed and implemented using Cisco Packet Tracer. This project simulates a real-world organizational network with multiple departments, secure communication, centralized services, VLAN segmentation, routing, redundancy, and network security configurations.

## Project Overview

This project demonstrates the design and implementation of a scalable campus network architecture for an organization with multiple departments. The network is segmented using VLANs and interconnected through Layer 3 routing to improve performance, security, and manageability.

The project applies industry-standard networking concepts commonly used in enterprise environments and serves as a practical implementation of CCNA-level networking skills.

---

## Objectives

* Design a structured enterprise network
* Implement VLAN-based network segmentation
* Enable communication between departments using Inter-VLAN Routing
* Configure dynamic IP addressing using DHCP
* Secure network traffic using ACLs
* Implement redundancy and fault tolerance
* Apply routing and switching best practices
* Simulate real-world enterprise networking scenarios

---

## Network Topology

### Departments

Building A – Business Operations Block
Management
HR
Finance

Building B – Technical Operations Block
Sales
Marketing
Operations

Building C – Management & Administration Block
IT Support
Research & Development (R&D)
Legal


Each department is assigned a dedicated VLAN and subnet to improve security and broadcast domain management.

---

## Technologies Used

* Cisco Packet Tracer
* Cisco IOS CLI
* Routing and Switching Technologies
* Network Security Features
* Enterprise Network Services

---

## Features Implemented

### Switching

* VLAN Configuration
* Trunking
* VLAN Trunking Protocol (VTP)
* EtherChannel
* Switch Virtual Interfaces (SVI)

### Routing

* Inter-VLAN Routing
* Router-on-a-Stick (ROAS)
* Static Routing
* Default Route

### Network Services

* DHCP Server
* DHCP Relay Agent
* DNS Services
  
---

## IP Addressing Plan

| Department     | VLAN | Subnet          |
| -------------- | ---- | --------------- |
| HR             | 10   | 10.0.0.0/8      |
| Sales          | 20   | 20.0.0.0/8      |
| Marketing      | 30   | 30.0.0.0/8      |
| IT Support     | 40   | 40.0.0.0/8      |
| R&D            | 50   | 50.0.0.0/8      |
| Operations     | 60   | 60.0.0.0/8      |
| Finance        | 70   | 70.0.0.0/8      |
| Legal          | 80   | 80.0.0.0/8      |
| Management     | 90   | 90.0.0.0/8      |

---

## Validation Performed

* VLAN communication tested
* Inter-VLAN routing verified
* DHCP address assignment validated
* ACL filtering verified
* OSPF neighbor relationships established
* NAT/PAT functionality tested
* SSH remote access verified
* End-to-end connectivity confirmed

---

## Learning Outcomes

Through this project, I gained hands-on experience in:

* Enterprise network design
* VLAN architecture
* Routing and switching
* Network security implementation
* High availability concepts
* Cisco IOS troubleshooting
* Real-world network deployment practices

---

## Project Files

This repository includes:

* Cisco Packet Tracer topology (.pkt)
* Network topology diagram
* Configuration files
* Project documentation
* Verification screenshots

---

## About Me

I am a Cyber Security Engineering student passionate about Networking, Cyber Security, and Cloud Technologies. This project showcases my practical networking skills and experience in designing and implementing enterprise network solutions.

### Connect With Me

* LinkedIn: https://www.linkedin.com/in/dhayalin-santhakumar-v-7999b4413/
* Email: dhayalin.dev@gmail.com
