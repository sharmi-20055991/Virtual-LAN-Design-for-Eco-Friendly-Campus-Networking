# Virtual-LAN-Design-for-Eco-Friendly-Campus-Networking

🧠 Concept

In a real network, VLANs (Virtual Local Area Networks) are configured on managed switches to separate departments logically — even though they share the same hardware.
In this Python version, we simulate the behavior of VLANs — showing how communication works within and across VLANs.

# Sample Output
Devices in VLAN 10 (Computer Science):
 - CS-PC1
 - CS-PC2

Devices in VLAN 20 (Electronics):
 - ECE-PC1

Devices in VLAN 30 (Administration):
 - ADMIN-PC1

CS-PC1 (VLAN 10) --> CS-PC2 (VLAN 10)
✅ Message delivered: "Hello CS team!"

CS-PC1 (VLAN 10) --> ECE-PC1 (VLAN 20)
❌ Message blocked: VLANs are different.

ECE-PC1 (VLAN 20) --> ADMIN-PC1 (VLAN 30)
❌ Message blocked: VLANs are different.

ADMIN-PC1 (VLAN 30) --> ADMIN-PC1 (VLAN 30)
✅ Message delivered: "Meeting Notice"

