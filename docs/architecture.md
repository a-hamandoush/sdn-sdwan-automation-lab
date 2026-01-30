# Purpose

Describe how the whole system is built.

## Architecture Overview

This project implements a hierarchical network architecture with centralized management and automation. The design follows the Access–Distribution–WAN–HQ model to ensure scalability, security, and high availability.

## Network Layers
### Access Layer

Provides connectivity for end devices such as PCs and IP phones. Implements VLAN segmentation and basic security controls.

### Distribution Layer

Aggregates access switches and provides redundancy and spanning-tree control.

### WAN Layer

Connects the branch to HQ via an ISP router.

### HQ Layer

Hosts centralized services and servers.

## Management Architecture

All configurations are managed via Git-based documentation and automated workflows. Planned future integration includes Ansible and SD-WAN controllers.

## Logical Diagram

See *docs/topology.md* for detailed topology.