# Threat Hunting Labs

Case studies from hands-on threat hunting practice using Zeek, RITA, and Wireshark against real malware packet captures.

## Investigations

| Lab | Description | Tools |
|-----|-------------|-------|
| [Zeus C2 Investigation](zeus-c2-investigation/) | Beaconing detection and fileless PowerShell downloader analysis | Zeek, RITA, Wireshark |

## About

These labs document the full workflow from raw packet capture to threat identification and IOC extraction:

1. Generate Zeek logs from a pcap
2. Import into RITA for automated beacon detection
3. Confirm findings in Wireshark at the packet level
4. Extract indicators of compromise (IOCs)
5. Document the investigation for a SOC/IR audience

## Tools Used

- **Zeek** — network security monitor, protocol log generation
- **RITA** — beaconing detection, DNS analysis, threat intel correlation
- **Wireshark** — packet-level analysis and stream reconstruction

## Background

27 years in hardware and network support, with a focus on incident response in multi-site retail environments. Transitioning into security operations with Security+, ISC2 CC, and hands-on lab work.
