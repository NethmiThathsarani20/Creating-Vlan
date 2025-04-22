# Cisco Switch VLAN Configuration

This repository documents a basic VLAN configuration on a Cisco switch, including:
- Creating VLANs (QA, DEV, Sales, HR)
- Assigning access ports to specific VLANs
- Verifying the configuration with `show vlan brief`

## Configuration Details

### VLANs Created:
- VLAN 10: QA
- VLAN 20: DEV
- VLAN 30: Sales
- VLAN 40: HR

### Port Assignments:
- Fa0/2-3 → VLAN 10 (QA)
- Fa0/6-9 → VLAN 20 (DEV)
- Fa0/1 & Fa0/5 → VLAN 30 (Sales)
- Fa0/13-15 → VLAN 40 (HR)

## Usage
This configuration serves as an example for:
- Basic Cisco switch VLAN setup
- Interface range configuration
- VLAN port assignment
- Configuration verification

Ideal for networking students or professionals looking for a simple VLAN configuration reference.
