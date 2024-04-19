# Penetration Testing Guide

This repository provides a basic guide for penetration testing. Penetration testing is a simulated cyber attack where professional ethical hackers break into corporate networks to find weaknesses... before attackers do.

## Prerequisites

Before you start with penetration testing, ensure you have the following:

1. Permission: Always have explicit permission to test.
2. Tools: Some of the common tools include Nmap, Metasploit, Wireshark, Burp Suite, OWASP ZAP, etc.

We will use oracale virtualbox in windows 10, Kali linux virtual image, Wifi Adapter Tp Link Archer T4U.

## Steps for Basic Penetration Testing

1. **Planning and Reconnaissance**: Define the scope and goals of a test, including the systems to be addressed and the testing methods to be used. Gather intelligence (e.g., network and domain names, mail servers) to better understand how the target works and its potential vulnerabilities.

2. **Scanning**: Use tools to understand how the target application will respond to various intrusion attempts. This is typically done using static analysis and dynamic analysis.

3. **Gaining Access**: Use web application attacks, such as cross-site scripting, SQL injection and backdoors, to uncover a target's vulnerabilities. Testers then try and exploit these vulnerabilities, typically by escalating privileges, stealing data, intercepting traffic, etc., to understand the damage they can cause.

4. **Maintaining Access**: The goal here is to see if the vulnerability can be used to achieve a persistent presence in the exploited system—long enough for a bad actor to gain in-depth access. The idea is to imitate advanced persistent threats, which often remain in a system for months in order to steal an organization's most sensitive data.

5. **Analysis**: The results of the penetration test are then compiled into a report detailing:

   - Specific vulnerabilities that were exploited
   - Sensitive data that was accessed
   - The amount of time the tester was able to remain in the system undetected

## Network Penetrating

### Set up virtual box

[oracle virtual box](https://www.virtualbox.org/wiki/Downloads)

### Install Kali Image

[Zsecurity Kali Image](https://zsecurity.org/download-custom-kali/)

### Setup Wireless Adapter

1. Get a external wireless adapter like TP LINK ARCHER T4U.

2. Disable the Wifi adapter from host machine. It can be done in windows from Control Panel -> Network & Internet -> Network Connections.

3. Open Virual Box.

4. Select Kali Image (Do not Start).

5. Select Settings.

6. Select USB.

7. Enable USB and Select a version (Example USB 3).

8. Add a USB filter and choose the adapter.

9. Except Name Vendor and Product remove all data and chose any from Remote Dropdown.

10. After creating filter save settings and remove the adapter physical connection to PC.

11. Start Kali linux.

12. After successfull boot wait a while then connect the adapter.

13. Check the connection from kali.

## Disclaimer

This guide is for educational purposes only. Penetration testing should only be performed with explicit permission from the network owner.
