# Networking Module 2

## Public IP vs Private IP

### Private IP

Private IP addresses are used inside local networks such as homes and offices.

Examples:

192.168.0.10

192.168.0.15

192.168.1.50

Devices inside the same network use private IP addresses to communicate.

### Public IP

Public IP addresses are visible on the Internet.

Examples:

8.8.8.8

1.1.1.1

A home network usually shares one public IP address through a router.

---

## IPv4 vs IPv6

### IPv4

IPv4 addresses use numbers separated by dots.

Examples:

192.168.0.1

8.8.8.8

142.250.151.102

### IPv6

IPv6 addresses use hexadecimal characters separated by colons.

Examples:

2001:4860:4860::8888

2a00:1450:4009:c13::8b

IPv6 was created because the Internet needed more IP addresses.

---

## Default Gateway

A Default Gateway is the device that connects a local network to other networks.

In most home networks, the Default Gateway is the router.

Example:

Laptop: 192.168.0.15

Router: 192.168.0.1

When a device wants to access the Internet, it sends traffic to the Default Gateway.

---

## Subnet Mask

A Subnet Mask helps identify which part of an IP address represents the network and which part represents the device.

Common subnet mask:

255.255.255.0

Example:

192.168.5.10

192.168.5.200

With the subnet mask 255.255.255.0, both devices are in the same network because the first three numbers are the same.

Example of different networks:

192.168.5.10

192.168.6.10

These devices are in different networks because the network portion is different.

---

## Key Points

- Private IP = local network address.
- Public IP = Internet-visible address.
- IPv4 uses dots.
- IPv6 uses colons.
- Default Gateway is usually the router.
- Subnet Mask identifies the network portion of an IP address.

---

## Date Studied

June 2026

## Source

Self-study Networking Lab
