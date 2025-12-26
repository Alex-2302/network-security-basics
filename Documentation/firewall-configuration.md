# Firewall Configuration

Windows Defender Firewall was configured on the Windows 11 virtual machine.

## Default-Deny Policy
- All inbound connections were blocked by default
- Outbound connections were allowed

This reduces the attack surface by preventing unsolicited inbound traffic.

## Custom Firewall Rules
### ICMP Allow Rule
- Allowed ICMP (ping) traffic only from the Kali Linux VM
- Demonstrates granular access control

### ICMP Block Rule
- A rule was created to block ICMP traffic
- When enabled, ping requests from Kali failed

## Stateful Firewall Behavior
Windows Defender Firewall is stateful, meaning it allows return traffic for permitted
connections while blocking unauthorized inbound attempts.

## Logging
Firewall logging was enabled to record allowed and blocked packets for monitoring and
troubleshooting purposes.
