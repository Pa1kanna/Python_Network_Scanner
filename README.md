# Python Network Scanner 🔍

A lightweight, efficient network port scanner built with Python. This tool utilizes the `socket` library to identify live hosts and discover open ports, simulating the foundational mechanics of enterprise reconnaissance tools like Nmap.

## Objective
The purpose of this project is to demonstrate a hands-on understanding of network protocols, TCP handshakes, and socket programming in a cybersecurity context. 

## Features
* **IPv4 Resolution:** Automatically translates hostnames to IPv4 addresses.
* **Targeted Scanning:** Scans the most common ports (1-1024) to identify vulnerable entry points.
* **Error Handling:** Built-in exceptions for clean exits during Keyboard Interrupts, unresolved hostnames, or dropped connections.

## Prerequisites
This script requires no external libraries. It uses Python's standard libraries:
* `socket`
* `sys`
* `datetime`

## Usage
Run the script via the command line, providing the target IP address or hostname as an argument.

```bash
# Example syntax
python3 scanner.py <target-ip>

# Example usage
python3 scanner.py 192.168.1.1
