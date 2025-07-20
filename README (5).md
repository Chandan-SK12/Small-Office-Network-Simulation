# Small Office Network Simulation

## 📝 Description
This project simulates a basic small office network using Cisco Packet Tracer. It includes two departments (Admin and Sales), VLANs, IP subnetting, and basic router configuration.

## 💡 Topology
  - 1 Router
  - 2 Switches
  - 2 PCs (Admin, Sales)
  - 1 Server (DHCP or DNS)
  - VLAN 10: Admin
  - VLAN 20: Sales

## 🌐 IP Addressing
| Device    | IP Address  | VLAN |
| Router    | 192.168.1.1   | --- |
| Admin PC  | 192.168.1.10  | 10   |
| Sales PC  | 192.168.2.10  | 20   |
| Server    | 192.168.3.10  | 30   |

## ⚙️ Features
- VLAN Configuration
- Inter-VLAN Routing
- DHCP Server Setup
- Static IP assignments (can switch to DHCP)

## 📂 How to Use
1. Open `.pkt` file in Cisco Packet Tracer.
2. Review topology and configs.
3. Ping between devices to test connectivity.