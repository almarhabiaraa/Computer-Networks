# LogiNet: Multi-Site Logistics Network Design
- Course: CS2091 – Computer Networks
- Tool Used: Cisco Packet Tracer
- Project Type: Network Simulation

## Introduction
LogiNet is a simulated multi-site logistics network designed using Cisco Packet Tracer as part of the CS2091 Computer Networks course. This project models the network infrastructure of a medium-sized logistics company with multiple branches, warehouses, and regional offices across different cities. The network supports a range of departments responsible for operations such as procurement, logistics, IT, and customer support.

The goal of this simulation is to create a functional, scalable, and secure network that provides internet access, inter-branch communication, and internal connectivity for each department using real-world networking principles.


## Repository Structure
```bash
├── Networks_project.pkt     # Cisco Packet Tracer project file containing the full network design
└── project_report.pdf       # Detailed project documentation and analysis
```

## Network Design

### Organization Overview
The network is designed for a medium-sized logistics company with:

- **Two main branches** (regional offices)
- **Warehouses and distribution centers** for operations across regions
- **Multiple internal departments**, including:
  - Procurement
  - Sales & Marketing
  - Transportation & Logistics
  - Customer Service
  - Finance
  - IT (located at the main office)

Each site is equipped with the necessary network infrastructure to ensure secure, stable, and efficient communication between branches and departments.

### End Devices
Each branch or LAN is equipped with:

- 🖥️ **6 PCs** – One per department  
- 💻 **1 Laptop**  
- 🖨️ **1 Printer** (main office only)

Key characteristics of the end devices:

- All devices are connected to a **local switch**
- Devices obtain IP addresses via **DHCP**
- Devices have **internet access** and can communicate across the network

### Intermediate Devices
Each LAN includes the following network components:

- **Router** – Acts as the **default gateway** and connects to other branches
- **Switch** – Connects all end devices within the local network
- **Server** – Provides **DHCP services**, assigning dynamic IP addresses and gateway info

The design ensures:

- Efficient routing and switching between sites
- Seamless IP address management using DHCP
- Scalable architecture for future expansion

## Key Features
- End-to-end device connectivity
- Branch-to-branch communication
- DHCP configuration for dynamic IP assignment
- Realistic simulation using Cisco Packet Tracer
- Printer integration for main office
- Modular design for easy expansion

## How to Set Up
1. Open Cisco Packet Tracer.
2. Load the file: Networks_project.pkt.
3. Power on all devices (if needed).
4. Observe DHCP configuration, ping between devices, and verify printer access.
5. Refer to project_report.pdf for full documentation and analysis.

## Contributors
1. Araa Almarhabi
2. Duaa Suroor
3. Ghazal Simbawah
