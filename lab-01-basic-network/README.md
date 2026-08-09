# Lab 01 — Basic Network Design

## Objective

Build a simple local network and verify connectivity between devices.

## Network Topology

- 2 PCs
- 1 Cisco Switch
- Ethernet connections

## IP Addressing

| Device | IP Address | Subnet Mask |
|--------|------------|-------------|
| PC1 | 192.168.1.10 | 255.255.255.0 |
| PC2 | 192.168.1.20 | 255.255.255.0 |

## Configuration

PC1:
- IP Address: `192.168.1.10`
- Subnet Mask: `255.255.255.0`

PC2:
- IP Address: `192.168.1.20`
- Subnet Mask: `255.255.255.0`

## Connectivity Test

From PC1, test connectivity to PC2:

```bash
ping 192.168.1.20
