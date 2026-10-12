# Experiment 14: How to Run an Nmap Scan

## Aim
Learn to run an Nmap scan using Nmap/Zenmap and interpret scan results.

## Requirements
- Computer with the relevant tool/simulator installed
- Authorized local lab target or simulator environment
- Folder to save output and screenshots

## Procedure
1. Download Nmap only from the official Nmap website: https://nmap.org/download.html.
2. Install Nmap and, if offered, include Zenmap (the graphical interface).
3. Open Nmap or Zenmap.
4. Enter a target you own or have explicit permission to test, such as 127.0.0.1 or your own lab host IP.
5. Choose an appropriate profile. A ping scan checks whether hosts appear online; a regular scan checks common ports; intensive profiles may be intrusive.
6. Start the scan and inspect the output and available Ports/Hosts, Topology, and Host Details tabs.
7. Save the output and capture a screenshot for your practical record.

## Commands / examples

### Loopback/basic local check
```text
nmap 127.0.0.1
```

### Ping scan for an authorized lab subnet
```text
nmap -sn 192.168.1.0/24
```

### Service/version detection for an authorized lab host
```text
nmap -sV <authorized-target-IP>
```

## Observation table

| No. | Test / configuration | Observed result | Evidence file |
|---:|---|---|---|
| 1 | Initial run | Fill in after your run | `evidence/` |
| 2 | Changed configuration / second test | Fill in after your run | `evidence/` |

## Result
Write the result only after completing the practical and checking the actual output.

## Conclusion
This experiment helps study the relevant network tool/simulator and interpret its results.

## Important notes
Replace example addresses with your own lab targets. Do not scan networks or devices without permission.

## Evidence checklist
- [ ] Screenshot of setup or topology
- [ ] Screenshot of command/configuration
- [ ] Screenshot of actual output/results
- [ ] Record the date, environment, and parameters changed
