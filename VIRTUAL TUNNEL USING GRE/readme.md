# Cisco GRE Tunnel VPN Implementation

## Project Overview

This project demonstrates the implementation of a GRE (Generic Routing Encapsulation) Tunnel between two remote enterprise networks using Cisco Packet Tracer.

The network simulates a real-world site-to-site VPN environment where two geographically separated offices communicate securely through a virtual tunnel established across an intermediate ISP network.

The GRE tunnel enables communication between the Head Office (H.O) and Branch Office (B.R.O) networks by encapsulating traffic and creating a logical point-to-point connection between routers.

---

## Technologies and Concepts Used

- Cisco Packet Tracer
- GRE Tunnel Configuration
- Virtual Tunnel Interfaces
- Site-to-Site VPN Concepts
- IP Routing
- Cisco IOS CLI
- Enterprise WAN Connectivity
- Network Verification and Troubleshooting

---

## Network Topology

The topology consists of:

- Head Office Router
- Branch Office Router
- ISP Router
- Cisco Switches
- Multiple End Devices (PCs)
- GRE Virtual Tunnel Connection

### Configured Networks

| Network | Purpose |
|----------|----------|
| 192.168.1.0/24 | Head Office LAN |
| 192.168.2.0/24 | Branch Office LAN |
| 200.1.1.0/24 | WAN Link |
| 200.1.2.0/24 | WAN Link |
| 172.16.1.0/30 | GRE Tunnel Network |

---

## Network Features

### GRE Tunnel Configuration
Configured a GRE virtual tunnel between the Head Office and Branch Office routers.

### Virtual Point-to-Point Connectivity
Established logical connectivity between remote sites using tunnel interfaces.

### Encapsulation of Traffic
Enabled encapsulation of private network traffic through the GRE tunnel across the WAN infrastructure.

### End-to-End Connectivity
Verified successful communication between hosts located in different office networks.

### Enterprise WAN Simulation
Simulated enterprise branch connectivity through an ISP network.

---

## Verification and Testing

The following verifications were successfully completed:

- GRE tunnel configuration verification
- Tunnel interface status verification
- Tunnel encapsulation verification
- Routing table verification
- Successful end-to-end connectivity testing
- Remote network communication validation

---

## Verification Commands Used

```bash
show running-config
show ip interface brief
show interface tunnel0
show ip route
ping [destination-ip]
tracert [destination-ip]
```

---

## Project Structure

```text
Cisco-GRE-Tunnel-VPN-Implementation/

├── README.md
├── gre-tunnel-lab.pkt
├── topology.png

└── screenshots/
    ├── topology.png
    ├── gre-tunnel-config.png
    ├── tunnel-interface-status.png
    ├── routing-table.png
    ├── tunnel-verification.png
    ├── end-to-end-ping.png
    └── traceroute-test.png
```

---

## Skills Demonstrated

- GRE tunnel implementation
- Virtual tunnel configuration
- Enterprise WAN networking
- Site-to-site VPN concepts
- Cisco router configuration
- Routing and connectivity verification
- Network troubleshooting
- Cisco IOS CLI administration

---

## Screenshots Included

### GRE Tunnel Configuration
Displays GRE tunnel interface configuration and tunnel parameters.

### Tunnel Interface Status
Shows operational tunnel interface status (`up/up`).

### Routing Table Verification
Displays routes learned and forwarded through the GRE tunnel.

### Tunnel Verification
Shows GRE encapsulation and tunnel operational details.

### End-to-End Connectivity Testing
Demonstrates successful communication between Head Office and Branch Office devices.

### Traceroute Verification
Shows packet traversal through the GRE tunnel infrastructure.

---

## Author

Mustansir Lokhandwala
