# Containerlab CCNP Labs

This repository contains a collection of CCNP-level networking labs built using **Containerlab**.  
All labs are defined using **YAML topology files** and are designed to be lightweight, repeatable, and easy to version control.

The goal of this project is to support hands-on CCNP preparation by modeling realistic enterprise network scenarios, focusing on routing, switching, and network services.

---

## Repository Structure

```text
Containerlab-CCNP-Labs/
├── labs/
│   ├── ospf/
│   ├── bgp/
│   ├── eigrp/
│   ├── switching/
│   └── mixed-scenarios/
├── startup-configs/
│   ├── lab-name/
│   │   ├── r1.cfg
│   │   ├── r2.cfg
│   │   └── sw1.cfg
├── images/
│   └── topology-diagrams/
├── README.md
```

- labs/
Containerlab YAML files defining each lab topology

- startup-configs/
Optional startup configurations applied at lab deployment

- images/
Diagrams or screenshots for lab reference

## Technologies Used

- Containerlab
- Docker
- Cisco IOS-XE / IOS-XR / NX-OS (container-based images where applicable)
- Linux-based networking containers (as needed)

## Lab Focus Areas
Planned and existing labs cover topics such as:
- Layer 2 switching fundamentals
- VLANs, trunking, and STP
- OSPF (single-area and multi-area)
- BGP (iBGP, eBGP, path selection)
- Route redistribution
- First-hop redundancy concepts
- Enterprise-style mixed routing scenarios

Labs are built to mirror real-world operational behaviors, not just exam theory.

## Prerequisites
To run these labs locally, you will need:
- Docker installed and running
- Containerlab installed\
https://containerlab.dev/install/
- Appropriate network OS container images
