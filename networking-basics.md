# Networking Basics - Writeup

## Objective
Understand how to identify services running on a target machine.

## Tools Used
- Nmap

## Steps Taken
1. Started with a basic scan:
   nmap -sC -sV <target IP>

2. Identified open ports:
   - Port 22 → SSH
   - Port 80 → HTTP

3. Analyzed service versions to understand potential vulnerabilities

## Why This Matters
Open ports expose services that attackers can target.  
Enumeration is the first and most important step in penetration testing.

## Key Takeaways
- Nmap helps discover attack surfaces
- Services running on open ports can be exploited
- Enumeration is critical before any attack
