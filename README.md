# Smart Integrated Network System on Cisco Packet Tracer

**Smart Integrated Network System on Cisco Packet Tracer** is a connected-campus network simulation. Its design separates endpoints into four zones and brings together wired access, wireless connectivity, and IoT devices.

## Overview

The network is organized into Office, Home, School, and University zones. Access switches connect wired clients, and a wireless router and IoT server provide connectivity for the simulated smart devices. Together, these elements demonstrate a segmented campus design and the core concepts used to connect users and IoT endpoints.

## Network topology

![Smart Integrated Network System campus topology in Cisco Packet Tracer](Screenshot%202026-10-14%20032228.png)

| VLAN | Zone | Endpoint overview |
| --- | --- | --- |
| 10 | Office | Desktop PCs and office IoT devices |
| 20 | Home | Desktop PCs, laptops, and home IoT devices |
| 30 | School | Desktop PCs and school IoT devices |
| 40 | University | Desktop PCs and university IoT devices |

Access switches connect wired endpoints across the zones. A WRT300N wireless router and an IoT server support wireless and IoT connectivity in the topology.

## Device inventory

### Network infrastructure

- Cisco Catalyst 2960-24TT access switches
- WRT300N wireless router
- IoT server

### Wired end devices

- Desktop PCs in the Office, Home, School, and University zones
- Laptops in the Home zone

### IoT devices by zone

| Zone | Devices shown |
| --- | --- |
| Office | Fan, appliance, light, window, siren |
| Home | Home speaker, siren, humidifier, light, webcam, furnace, garage door |
| School | Door, webcam, fan, siren, temperature monitor |
| University | Light, battery, webcam, motion detector, fan, solar panel, street lamp |

## Technologies and networking concepts

| Technology | Application |
| --- | --- |
| Cisco Packet Tracer | Topology design and network simulation |
| VLANs | Logical separation of the four campus zones |
| Inter-VLAN routing | Communication between network segments |
| DHCP | Dynamic IP address assignment |
| WPA2-Enterprise and RADIUS | Secure wireless authentication |
| Access control lists (ACLs) | Traffic filtering and access control |
| Layer 2 and Layer 3 switching | Wired network access and forwarding |
| IoT services | Connectivity and management of simulated smart devices |
| ICMP | Basic network connectivity testing |

This project is a simulation, not a production network deployment. Available features and device behavior depend on the Packet Tracer version and the configuration saved in the project.

## Prerequisites

- Cisco Packet Tracer installed on your computer

## Open the simulation

1. Launch Cisco Packet Tracer.
2. Open `Smart Integrated Network System.pkt`.
3. Use **Realtime** mode to inspect device status and perform connectivity tests.
4. Select a router, switch, server, or endpoint to review its configuration.
5. Use **Simulation** mode to observe packet flow and troubleshoot communication.

## Testing and verification

- Confirm that endpoints receive the expected IP configuration.
- Test connectivity between endpoints in the same VLAN.
- Verify intended inter-VLAN connectivity and ACL behavior.
- Check wireless authentication and IoT connectivity.
- Inspect packet paths in **Simulation** mode when troubleshooting.

## License

This project is made available under the [MIT License](https://opensource.org/licenses/MIT). Use, modification, and redistribution are permitted provided that the copyright and license notice are retained.

## Author

**Malik Lateef**  
Software Engineering Student · Lahore, Pakistan  
[imaliklateef@gmail.com](mailto:imaliklateef@gmail.com)

*A networking portfolio project demonstrating campus segmentation, routing, wireless security, and IoT integration in Cisco Packet Tracer.*
