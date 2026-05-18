# Task 1: Host Reconnaissance & Vulnerability Assessment

**Status:** Completed  
**Objective:** Perform proactive host reconnaissance, network mapping, and OS fingerprinting using automated utilities to discover active services and analyze the attack surface of a remote target.

### Methodology
- Target Environment: scanme.nmap.org
- Scanning Engine: Leveraged the Zenmap GUI backed by Nmap 7.99.
- Scan Configuration: Executed an Intensive Scan with OS and version detection using the parameters: nmap -T4 -A -v.
- Script Auditing: Ran 158 Nmap Scripting Engine (NSE) scripts to cross-reference discovered protocols against known misconfigurations.

### Tools Used
- Nmap / Zenmap (Intensive Scan Engine)
