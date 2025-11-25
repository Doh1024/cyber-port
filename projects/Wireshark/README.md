# Wireshark Packet Analysis

This project highlights my hands-on practice with Wireshark, focusing on capturing and analyzing network traffic in a controlled lab environment. The goal was to learn how to navigate the interface, apply filters, understand traffic patterns, and use built-in analysis tools.

## What I learned

- Navigated through the Wireshark interface and understood the layout

- Captured live packets using different network interfaces

- Applied display filters (e.g., http, dns, tcp.flags.syn == 1) to isolate specific traffic

- Used colorization rules to highlight important traffic for faster analysis

- Created custom profiles to streamline the workflow

- Explored the Statistics tab (Protocol Hierarchy, Conversations, Endpoints, IO Graphs)

## Examples

- Identified the TCP 3-way handshake in packet traces 
![TCP Handshake](./screenshots/handshake.png)
- Traced DNS request/response flows
![DNS Query](./screenshots/dns_query.png)

## Next Steps

- TLS handshake analysis

- Detecting ARP spoofing in a lab

- Analyzing basic malware traffic in an isolated environment

- Using IO graphs for deeper performance insights