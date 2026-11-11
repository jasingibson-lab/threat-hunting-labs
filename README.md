# Threat Hunting Labs

Case studies from hands-on threat hunting practice using Zeek, RITA, and Wireshark against real malware packet captures.

## Investigations

| Lab | Description | Tools |
| :--- | :--- | :--- |
| [Zeus C2 Investigation](zeus-c2-investigation) | Beaconing detection and fileless PowerShell downloader analysis | Zeek, RITA, Wireshark |
| [PittyTiger C2 Investigation](pittytiger) | Beaconing to a jittered C2, analysis of an APT-style RAT | Zeek, RITA, Wireshark |
| [Home Network Baseline](homenet-baseline) | Baseline analysis of a home network, device inventory, host traffic leak observation | Zeek, RITA, Wireshark |
| [DVWA LAMP Pentest Lab](dvwa-lamp-pentest-lab) | Build a vulnerable web server, execute a full pentest, and analyze the logs. | Nmap, Hydra, Zeek, UFW |
| [Fiesta C2 Analysis](fiesta) | Post-infection Cobalt Strike beaconing analysis | Zeek, RITA, Wireshark |

## About

These labs document the full workflow from raw packet capture to threat identification and IOC extraction:

1. Generate Zeek logs from a pcap
2. Import logs into RITA and analyze beacon scores
3. Pivot to Wireshark for packet-level investigation and IOC extraction
