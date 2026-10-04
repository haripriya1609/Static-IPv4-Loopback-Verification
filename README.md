# Single-Host Static IPv4 Addressing & Local Loopback Verification

## Objective

To configure static IPv4 addressing on PC0 using Cisco Packet Tracer and verify the TCP/IP stack using ping commands.

## IP Configuration

* Device: PC0
* IPv4 Address: 192.168.10.25
* Subnet Mask: 255.255.255.0
* Default Gateway: 192.168.10.1
* DNS Server: 8.8.8.8

## Commands Used

```bash
ipconfig
ping 127.0.0.1
ping 192.168.10.25
```

## Result

Static IPv4 configuration was completed successfully. The loopback and assigned IP address ping tests were successful with 0% packet loss.

## Tool Used

Cisco Packet Tracer 9.0.1

## Project File

firsttask.pkt
