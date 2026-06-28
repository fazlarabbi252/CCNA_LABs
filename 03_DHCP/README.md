## 03 cisco swtich configurations with dhcp

This project demonstrates devices get auto IP(DHCP) in a network.

## Network Configuration Details
- **Laptop0:** use for configure the switch DHCP
- **Laptop1:** use a a client which get auto IP & Gateway
- **Laptop2:** use a a client which get auto IP & Gateway

## How to Test
1. Open `switch configure(VLANs).pkt` in Cisco Packet Tracer.
2. password of switch is :`123`
3. In client laptop command prompt run : `ipconfig /renew` to get the DHCP IP
4. In configure laptop terminal run in(Privileged EXEC Mode) : `show ip dhcp binding` to check DHCP. and `show ip dhcp pool` to check the DHCP pool

