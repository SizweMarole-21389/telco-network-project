# TELCO Network Project — Work-Integrated Learning (WIL)

## Overview
This Work-Integrated Learning (WIL) project covers the design and planning of a telecommunications network infrastructure. It includes full project documentation, a network topology diagram, and a formal project report produced as part of practical industry experience.

## Project Files

| File | Description |
|---|---|
| `WIL_TELCO_PROJECT_DOCUMENTATION.pdf` | Complete project documentation report |
| `TELCO.docx` | Project write-up and technical narrative |
| `WIL_TOPOLOGY (2).png` | Network topology diagram |

## Key Topics Covered
- Telecommunications network architecture and planning
- Network topology design for TELCO infrastructure
- Service provider network concepts
- WIL industry engagement and professional practice

## Context
Produced as part of the Work-Integrated Learning (WIL) programme, this project reflects real-world telecommunications design work undertaken during an industry placement.

---

## Network Topology Diagram

**WIL_TOPOLOGY (2).png**

This diagram is titled "Advanced Enterprise Networking Project - Nelson Tech" and presents a comprehensive hierarchical network topology for a multi-floor enterprise environment. The design demonstrates a three-tier network architecture consisting of core, distribution, and access layers.

At the top of the diagram, the WAN and internet connectivity layer is shown. An orange-bordered zone in the upper left represents the WAN segment, containing WAN routers configured with point-to-point addressing in the 10.10.10.x/30 subnet range and a wider network in the 80.20.50.x/25 range. External ISP connections are shown in the upper right with public-facing IP addresses in the 80.10.0.x and 10.30.x.x ranges, representing internet uplinks.

A central routing and switching core is shown in the middle of the diagram, enclosed in a yellow cloud shape. This core layer connects the WAN uplinks to the internal campus distribution infrastructure and includes routing protocol configuration details (OSPF) visible in the annotation text on the right side of the topology.

The lower portion of the diagram is divided into two large zones representing different floors or departments within the headquarters building. The left zone, enclosed in a purple border and labelled with a floor designation, shows a distribution switch feeding multiple access layer switches. Each access switch serves a cluster of end-user workstations and laptops, colour-coded in shades of blue, green, and orange to indicate separate VLANs or network segments. This zone demonstrates VLAN-based segmentation at the access layer for logical traffic separation.

The right zone, similarly bordered, represents another floor or department. It mirrors the hierarchical switching structure, with a distribution switch at the top branching down to access switches serving workstations and specialised devices including what appear to be servers or network-attached devices in a pink-shaded segment.

Inter-VLAN routing is handled at the distribution layer, and the topology illustrates a practical implementation of industry-standard enterprise network design principles including redundancy, segmentation, and centralised routing.
