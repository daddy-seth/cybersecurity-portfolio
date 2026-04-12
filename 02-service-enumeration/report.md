# Service Enumeration with Nmap

## Objective
To identify open ports and running services on a target system.

## Tool Used
- Kali Linux
- Nmap

## Command Used
nmap -sV -T4 --top-ports 100 10.0.2.15

## Results
- All scanned ports were filtered (no response)
- No open services detected

## Analysis
- The system is not exposing any services
- Traffic is likely filtered by VirtualBox NAT or firewall
- This indicates a secure configuration with minimal attack surface

## Key Learning
- Understood port states (open, closed, filtered)
- Learned service enumeration techniques
- Recognized how secure systems behave during scans

## Next Step
Perform packet analysis using Wireshark<img width="1348" height="838" alt="nmap-scan pnp 2" src="https://github.com/user-attachments/assets/88d0e819-d46d-4924-bd26-5bd8fb46f0d0" />
