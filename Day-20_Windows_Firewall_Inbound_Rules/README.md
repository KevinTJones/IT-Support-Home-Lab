# Day 20 – Windows Firewall Inbound Rules (DHCP)

## Objective
Verify that essential Windows Defender Firewall inbound rules are enabled to allow basic network functionality, focusing on DHCP traffic required for IP address assignment.

## Tools Used
- Windows Defender Firewall with Advanced Security

## Steps Performed
1. Opened **Windows Defender Firewall with Advanced Security**
2. Navigated to **Inbound Rules**
3. Reviewed core networking rules related to system connectivity
4. Identified and verified the **Core Networking – DHCP (UDP-In)** rule
5. Confirmed the rule status was **Enabled**

## Findings
- The DHCP inbound rule was enabled and active.
- This confirms the system can receive IP configuration from a DHCP server.
- Without this rule, devices may fail to obtain an IP address, resulting in loss of network connectivity.

## Why This Matters
DHCP is a foundational network service. Ensuring firewall rules allow DHCP traffic prevents common issues such as:
- “No Internet access”
- APIPA (169.254.x.x) addresses
- Network connection failures after firewall changes

This check demonstrates understanding of firewall behavior and how security controls impact system availability.

## Evidence
- Screenshot showing **Core Networking – DHCP (UDP-In)** rule enabled in Windows Defender Firewall

## Outcome
Firewall configuration verified. No remediation required.
