# Network Configuration Notes

## Router (Basic Setup)
   - Enable
   - conf t
   - interface g0/0
   - address 192.168.1.1 255.255.255.0
   -  no shutdown
   - exit

## Switch-1
   - vlan 10
   -  name Admin
   -  vlan 20
   -  name Sales
   -  interface range f0/1 - 2
   -  switchport mode access
   - switchport access vlan 10

## Switch-2
  - interface range f0/1 - 2
  - switchport mode access
  - switchport access vlan 20

## PC Configuration (Manual)
  - IP: 192.168.1.10 (Admin PC)
  - IP: 192.168.2.10 (Sales PC)
  - Subnet Mask: 255.255.255.0
  - Gateway: 192.168.1.1

## Server (Optional DHCP Setup)
  - Configure DHCP pool with respective ranges and default gateway.