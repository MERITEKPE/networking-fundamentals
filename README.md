# networking-fundamentals
# Networking Fundamentals

This repository provides an overview of key networking concepts, including:

## **OSI Model**
The **Open Systems Interconnection (OSI) model** is a seven-layer framework for network communication:
1. **Physical Layer** – Deals with hardware transmission (e.g., cables, Wi-Fi).
2. **Data Link Layer** – Ensures reliable transmission using MAC addresses.
3. **Network Layer** – Handles IP addressing and routing.
4. **Transport Layer** – Ensures data delivery (e.g., TCP, UDP).
5. **Session Layer** – Manages sessions between applications.
6. **Presentation Layer** – Translates, encrypts, and compresses data.
7. **Application Layer** – Provides network services like HTTP and SMTP.

## **IP Addressing & Subnetting**
- Example: **192.168.1.0/24 subnetted into /26**
  - 4 Subnets:
    - **192.168.1.0/26** (Usable: 192.168.1.1 - 192.168.1.62)
    - **192.168.1.64/26** (Usable: 192.168.1.65 - 192.168.1.126)
    - **192.168.1.128/26** (Usable: 192.168.1.129 - 192.168.1.190)
    - **192.168.1.192/26** (Usable: 192.168.1.193 - 192.168.1.254)

## **TCP/IP Protocol Suite in a Real-World Scenario**
**Example: Loading a Web Page**
1. **Application Layer** – HTTP request is sent by the browser.
2. **Transport Layer** – TCP segments the request.
3. **Network Layer** – IP addresses guide the request to the destination.
4. **Data Link & Physical Layers** – Packets are transmitted via MAC addresses over the network.

## **Subnetting Screenshots**
Screenshots of the subnetting calculator results are available in the `screenshots/` directory.
