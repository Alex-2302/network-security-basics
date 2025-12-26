# Network Setup

A virtual lab environment was created using VirtualBox on a Linux Mint host system.

## Virtual Machines
- Windows 11 VM:
  - Used for firewall configuration and traffic monitoring
- Kali Linux VM:
  - Used only to generate network traffic

## Network Design
- Internal Network:
  - Provides full isolation
  - Allows communication only between the two virtual machines
  - No internet or host access
- NAT Network (temporary):
  - Used to capture DNS, HTTP, and HTTPS traffic

## IP Addressing
Static IP addresses were assigned within the internal network:
- Windows 11 VM: 192.168.100.10
- Kali Linux VM: 192.168.100.20

## Encryption
Internet access was provided via a mobile hotspot secured using WPA2/WPA3 encryption,
ensuring wireless traffic confidentiality.
