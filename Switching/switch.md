# Switching

Switching works at Layer 2 (Data Link Layer) of the OSI model.

A switch forwards frames using MAC addresses.

## Switch Operation

Example:

PC1 sends a frame:

PC1
 |
Switch
 |
PC2


The switch checks the destination MAC address and forwards the frame to the correct port.

## MAC Address Table

A switch learns which MAC address is connected to which port.

Example:

| MAC Address | Port |
|------------|------|
| AA:BB:CC:11:22:33 | Port 1 |
| DD:EE:FF:44:55:66 | Port 2 |

## Broadcast

When a switch does not know the destination MAC address, it floods the frame to all ports.

## VLAN

A VLAN creates separate logical networks inside a switch.