# BridgeNet Campus

A university campus network designed and implemented in **Cisco Packet Tracer** for the CSE421 project.

## Project Overview

BridgeNet Campus connects six departments of a simulated university:

- CSE
- EEE
- BBA
- Pharmacy
- LAW
- Research

The network uses **VLSM, DHCP, DNS, RIPv2, static routing, web servers, email servers, and floating static routes**.

## Main Features

- VLSM-based IP addressing using `15.76.0.0/16`
- Dynamic DHCP for departmental PCs
- Central DNS server
- Departmental web servers
- CSE and BBA email servers
- RIPv2 and static routing
- LAW-Research backup link for failover
- Inter-department connectivity testing

## Tools Used

- Cisco Packet Tracer
- IPv4
- RIPv2
- DHCP
- DNS
- HTTP
- SMTP / POP3

## Files

- `BridgeNet_Final.pkt` — Final Cisco Packet Tracer network
- `BridgeNet_Campus_Final_Project_Report.docx` — Project report

## How to Run

1. Open `BridgeNet_Final.pkt` in Cisco Packet Tracer.
2. Check the router and PC configurations.
3. Use `ping` to test connectivity between departments.
4. Test the DNS, websites, email, and backup routes.


