# Elevate-Labs-Intern
Objective
Understand and perform basic network reconnaissance to identify open ports on devices in your local network.

Tools Used
Nmap

Wireshark (optional)

Steps Followed
1.Install Nmap from the official website.

2.Identify the local IP range (e.g., 192.168.1.0/24).

3.Run TCP SYN scan using:
nmap -sS 192.168.1.0/24

4.Record all live hosts and open ports from the scan results.

5.(Optional) Capture and analyze packets with Wireshark to observe scan behavior.

6.Research common services running on detected open ports.

7.Identify potential security risks posed by the open ports.

8.Save the scan output as a text or HTML file for documentation.
