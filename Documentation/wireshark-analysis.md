# Wireshark Traffic Analysis

Wireshark was installed on the Windows 11 virtual machine to capture and analyze network traffic.

## ICMP Traffic
- ICMP echo requests and replies were observed when pinging from Kali
- When ICMP was blocked, requests were visible without replies

## DNS Traffic
- DNS queries were observed during the NAT network phase
- DNS traffic resolves domain names to IP addresses

## HTTP and HTTPS Traffic
- HTTP traffic was visible in plaintext
- HTTPS traffic appeared encrypted (TLS), demonstrating secure communication

## Observations
- Encrypted traffic cannot be read without decryption keys
- Firewall rules directly influenced packet behavior
- Wireshark provided visibility into normal and blocked traffic patterns
