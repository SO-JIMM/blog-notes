---
title: Ports & Port Numbers
date: 2022-08-09T15:39:35.083Z
description: The significance behind why we choose our port numbers
tag: backend, server
author: SO-JIMM
---

A port is a virtual point where network connections start and end. Ports are software-based and managed by a computer's operating system. Each port is associated with a specific process or service. Ports allow computers to easily differentiate between different kinds of traffic: emails go to a different port than webpages, for instance, even though both reach a computer over the same Internet connection.

There are 65,535 possible port numbers, although not all are in common use.

- **Ports 20** and **21**: File Transfer Protocol (FTP). FTP is for transferring files between a client and a server.
- **Port 22**: Secure Shell (SSH). SSH is one of many tunneling protocols that create secure network connections.
- **Port 25**: Historically, Simple Mail Transfer Protocol (SMTP). SMTP is used for email.
- **Port 53**: Domain Name System (DNS). DNS is an essential process for the modern Internet; it matches human-readable domain names to machine-readable IP addresses, enabling users to load websites and applications without memorizing a long list of IP addresses.
- **Port 80**: Hypertext Transfer Protocol (HTTP). HTTP is the protocol that makes the World Wide Web possible.
- **Port 443**: HTTP Secure (HTTPS). HTTPS is the secure and encrypted version of HTTP. All HTTPS web traffic goes to port 443. Network services that use HTTPS for encryption, such as DNS over HTTPS, also connect at this port.
- **Port 587**: Modern, secure SMTP that uses encryption.
- **Port 3389**: Remote Desktop Protocol (RDP). RDP enables users to remotely connect to their desktop computers from another device.

### References, Resources, Sources

[Cloudflare - What is a computer port?](https://www.cloudflare.com/en-gb/learning/network-layer/what-is-a-computer-port/)
