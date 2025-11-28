# Cisco DHCP Configuration Project

This project demonstrates how to configure DHCP on a Cisco router using Cisco Packet Tracer.

## 🔥 Features
- Router DHCP setup
- IP addressing
- Default gateway configuration
- DNS configuration
- Interface configuration and verification

## 🧩 Network Details
- DHCP Pool Name: MARUF-LAN / CONFIDENCE-LAN / AGR-LAN / TALUKDAR-LAN (based on topology)
- Example Network: 192.168.X.0/24
- DNS: 8.8.8.8 / 9.9.9.9 / 1.1.1.1

## 🔧 Basic DHCP Commands Used
- Router(config)# ip dhcp pool MARUF-LAN
- Router(dhcp-config)# network 192.168.125.0 255.255.255.128
- Router(dhcp-config)# default-router 192.168.125.1
- Router(dhcp-config)# dns-server 8.8.8.8
- Router(config)# interface fa0/0
- Router(config-if)# ip address 192.168.125.1 255.255.255.128
- Router(config-if)# no shutdown


## ✔ Output
Clients automatically receive:
- IP address
- Subnet mask
- Default gateway
- DNS server

## 📂 Files Included
- `.pkt` file (Packet Tracer topology)
- This README

