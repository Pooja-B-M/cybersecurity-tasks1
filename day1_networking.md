Day-1 Networking Basics for Cybersecurity (Detailed)
🔢 IPv4 (Internet Protocol Version 4)

IPv4 is used to identify devices on a network using a 32-bit address.

Example:

192.168.1.1

Key Points

32-bit addressing

Around 4.3 billion unique addresses

Still widely used across the internet

Often used with NAT (Network Address Translation)

Security Concerns

IP Spoofing: Attackers fake IP addresses to bypass security

Limited address space leads to NAT, which can hide attackers

Older protocol with no built-in encryption

🔢 IPv6 (Internet Protocol Version 6)

IPv6 was introduced to overcome IPv4 limitations using 128-bit addressing.

Example:

2001:db8:85a3::8a2e:370:7334

Key Points

Huge address space (almost unlimited)

No need for NAT

Faster and more efficient routing

Supports auto-configuration

Security Advantages

Built-in IPSec support

Better network segmentation

Harder to scan entire networks

Improved protection against spoofing

🌍 DNS (Domain Name System)

DNS converts human-readable domain names into IP addresses.

Example:

google.com → 142.250.195.78

Why DNS is Important

Makes the internet user-friendly

Used in almost every web request

Critical infrastructure service

Common DNS Attacks

DNS Spoofing: Fake DNS responses redirect users

DNS Hijacking: DNS settings are maliciously changed

Cache Poisoning: Fake data stored in DNS cache

Security Measures

DNSSEC

Secure DNS resolvers

Network monitoring

📡 DHCP (Dynamic Host Configuration Protocol)

DHCP automatically assigns network configuration details to devices.

DHCP Assigns

IP address

Subnet mask

Default gateway

DNS server

DHCP Process (DORA)

Discover – Client looks for DHCP server

Offer – Server offers IP configuration

Request – Client requests offered IP

Acknowledge – Server confirms assignment

Security Risks

Rogue DHCP servers

Man-in-the-Middle attacks

Network traffic interception

Mitigation

DHCP snooping

Port security

Network segmentation

🔐 VPN (Virtual Private Network)

A VPN creates a secure, encrypted tunnel over the internet to protect data.

Uses of VPN

Secure remote access

Safe browsing on public Wi-Fi

Hiding IP address

Protecting sensitive data

Types of VPN

Remote Access VPN – For individual users

Site-to-Site VPN – Connects two networks

Common VPN Protocols

OpenVPN

IPSec

L2TP

WireGuard

Security Risks

Weak or outdated encryption

Poor VPN configuration

Logging by VPN providers

DNS leaks

VPN malware or fake VPN apps

Best Practices

Use strong encryption

Disable split tunneling if not required

Choose trusted VPN providers

Regularly update VPN software

🔐 Cybersecurity Relevance (Why this matters)

Networking concepts are critical in cybersecurity because:

Most attacks occur over networks

Understanding traffic helps detect attacks

Network misconfiguration leads to breaches
