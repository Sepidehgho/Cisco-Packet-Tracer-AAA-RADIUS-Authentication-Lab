# Cisco-Packet-Tracer-AAA-RADIUS-Authentication-Lab
## Overview

This project demonstrates **AAA authentication using a RADIUS server** in Cisco Packet Tracer.

The goal of the lab is to configure a Cisco router as a **RADIUS client** and use a centralized AAA server to authenticate users.

## Network Topology

The topology contains:

- **Router0** – AAA / RADIUS client
- **Server0** – RADIUS authentication server
- **Switch0** – Layer 2 connectivity
- **Laptop0** – client device used for testing

### Connections

- Router0 → Switch0
- Server0 → Switch0
- Laptop0 → Switch0

## How It Works

1. A user tries to access the Cisco router.
2. The router sends the authentication request to the **RADIUS server**.
3. The RADIUS server checks the username and password.
4. If the credentials are correct, the server sends an **Access-Accept** message.
5. The router allows the user to log in.
6. If the credentials are incorrect, access is denied.

## Lab Objectives

This lab is used to practice:

- AAA configuration on Cisco devices
- Centralized user authentication
- RADIUS client/server configuration
- Remote login authentication
- Basic IP connectivity
- Testing and troubleshooting authentication

## Authentication Flow

User  
↓  
Cisco Router  
↓  
RADIUS Request  
↓  
RADIUS Server  
↓  
Access-Accept / Access-Reject

## Technologies Used

- Cisco Packet Tracer
- Cisco IOS
- AAA
- RADIUS
- IP Networking
- Ethernet Switching
