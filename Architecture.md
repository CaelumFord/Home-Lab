# Architecture

## Virtual Network Specifications:

- Network Type: VirtualBox NATNetwork
- Subnet Mask 255.255.255.0 / CIDR: 10.0.2.0/24
- Gateway IP: 10.0.2.1
- DHCP Range: 10.0.2.4 --> 10.0.2.254

## Virtual Network Topology Map:

[insert topology]


## Virtual Machine Inventory Table:

| Virtual Machine Name         | Windows Server      | Windows Machine     | Ubuntu Server        | Parrot Machine      |
|------------------------------|---------------------|---------------------|----------------------|---------------------|
| IP Address                   | 10.0.2.10           | 10.0.2.4            | 10.0.2.15            | 10.0.2.5            |
| Operating System & Version   | Microsoft Windows Server 2022 Standard Edition                                                                                                                  | Microsoft Windows 11 Pro                                                                                                                                        | Ubuntu 26.04.1 LTS                                                                                                                                              | Parrot Security 7.1 (Echo)                                                             |
| Mac Address                  | 08:00:27:A1:20:80   | 08:00:27:7B:3D:36   | 08:00:27:E1:BF:1A    | 08:00:27:D2:44:AE   |
| Function                     | Vulnerable Endpoint | SOC Analyst Workstation    | SIEM Manager and Indexer    | Red Team Attacking Node    |





