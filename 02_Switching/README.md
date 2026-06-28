## 02 cisco swtich configurations with VLANs

This project demonstrates VLANs routing in a network.

## Network Configuration Details
- **Laptop0:** 192.168.10.10 (SVIs/Gateway: 192.168.10.10)
- **Laptop1:** 192.168.20.10 (SVIs/Gateway: 192.168.20.10)
- **Laptop2:** use for configur the switch

## How to Test
1. Open `switch configure(VLANs).pkt` in Cisco Packet Tracer.
2. password of switch is :`123`
3. In configure laptop Command Prompt run in(Privileged EXEC Mode) : `show vlan brief` to check the VLANs.
4. Open Laptop0's Command Prompt and run: `ping 192.168.20.10`
