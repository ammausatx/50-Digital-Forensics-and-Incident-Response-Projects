# 50 Digital Forensics and Incident Response Projects

A practical portfolio of 50 hands-on DFIR exercises, progressing from evidence handling and endpoint triage to memory, network, cloud, and enterprise incident response.

## Collection status
- Beginner: **15/15 complete**
- Intermediate: **20/20 complete**
- Advanced: **15/15 complete**
- Overall: **50/50 complete**

Each project includes a walkthrough and three project-specific simulated training illustrations. The illustrations are educational mockups, not actual forensic screenshots or evidence from real investigations.

## Safety and evidence handling
Use only systems, images, logs, memory captures, cloud exports, and network captures you own or are explicitly authorized to examine. Preserve original evidence, work from verified copies, record SHA-256 hashes and chain of custody, normalize timestamps carefully, and redact personal or sensitive data. Do not execute live malware or suspicious document content. Cloud exercises use synthetic exports unless written tenant authorization is in place.

## Beginner projects (01–15)
- [Project 01: Forensic Workstation And Evidence Handling Baseline](projects/01-forensic-workstation-and-evidence-handling-baseline/README.md)
- [Project 02: Acquire A Forensic Disk Image With Guymager](projects/02-acquire-a-forensic-disk-image-with-guymager/README.md)
- [Project 03: Verify Evidence Integrity With Sha 256](projects/03-verify-evidence-integrity-with-sha-256/README.md)
- [Project 04: Analyze Disk Images With Autopsy](projects/04-analyze-disk-images-with-autopsy/README.md)
- [Project 05: Recover Deleted Files With Sleuth Kit](projects/05-recover-deleted-files-with-sleuth-kit/README.md)
- [Project 06: Windows Event Log Triage Workflow](projects/06-windows-event-log-triage-workflow/README.md)
- [Project 07: Investigate Windows Prefetch Artifacts](projects/07-investigate-windows-prefetch-artifacts/README.md)
- [Project 08: Analyze Windows Registry Evidence](projects/08-analyze-windows-registry-evidence/README.md)
- [Project 09: Examine Browser History And Downloads](projects/09-examine-browser-history-and-downloads/README.md)
- [Project 10: Investigate Usb Device Artifacts](projects/10-investigate-usb-device-artifacts/README.md)
- [Project 11: Triage Linux Authentication Logs](projects/11-triage-linux-authentication-logs/README.md)
- [Project 12: Analyze Linux Shell History And Persistence Artifacts](projects/12-analyze-linux-shell-history-and-persistence-artifacts/README.md)
- [Project 13: Create A Basic Incident Timeline](projects/13-create-a-basic-incident-timeline/README.md)
- [Project 14: Collect And Preserve Volatile Evidence Safely](projects/14-collect-and-preserve-volatile-evidence-safely/README.md)
- [Project 15: Write A Forensic Findings Report](projects/15-write-a-forensic-findings-report/README.md)

## Intermediate projects (16–35)
- [Project 16: Windows Memory Acquisition With Winpmem](projects/16-windows-memory-acquisition-with-winpmem/README.md)
- [Project 17: Analyze Memory Images With Volatility 3](projects/17-analyze-memory-images-with-volatility-3/README.md)
- [Project 18: Detect Suspicious Processes And Dlls In Memory](projects/18-detect-suspicious-processes-and-dlls-in-memory/README.md)
- [Project 19: Investigate Network Connections From Memory](projects/19-investigate-network-connections-from-memory/README.md)
- [Project 20: Extract And Analyze Windows Event Logs With Hayabusa](projects/20-extract-and-analyze-windows-event-logs-with-hayabusa/README.md)
- [Project 21: Build A Windows Endpoint Incident Timeline](projects/21-build-a-windows-endpoint-incident-timeline/README.md)
- [Project 22: Analyze Ntfs Mft And Usn Journal](projects/22-analyze-ntfs-mft-and-usn-journal/README.md)
- [Project 23: Recover Artifacts From Shadow Copies](projects/23-recover-artifacts-from-shadow-copies/README.md)
- [Project 24: Investigate Scheduled Tasks And Services](projects/24-investigate-scheduled-tasks-and-services/README.md)
- [Project 25: Analyze Linux Memory Artifacts](projects/25-analyze-linux-memory-artifacts/README.md)
- [Project 26: Investigate Ssh Compromise From Logs](projects/26-investigate-ssh-compromise-from-logs/README.md)
- [Project 27: Perform Pcap Based Incident Reconstruction With Wireshark](projects/27-perform-pcap-based-incident-reconstruction-with-wireshark/README.md)
- [Project 28: Analyze Dns And Http Evidence From Pcap](projects/28-analyze-dns-and-http-evidence-from-pcap/README.md)
- [Project 29: Investigate Email Headers And Message Routing](projects/29-investigate-email-headers-and-message-routing/README.md)
- [Project 30: Triage Suspicious Office Documents Safely](projects/30-triage-suspicious-office-documents-safely/README.md)
- [Project 31: Analyze Browser And Cloud Sync Artifacts](projects/31-analyze-browser-and-cloud-sync-artifacts/README.md)
- [Project 32: Investigate Ransomware Impact Using Safe Artifacts](projects/32-investigate-ransomware-impact-using-safe-artifacts/README.md)
- [Project 33: Build An Endpoint Detection And Response Triage Case](projects/33-build-an-endpoint-detection-and-response-triage-case/README.md)
- [Project 34: Correlate Siem Endpoint And Network Evidence](projects/34-correlate-siem-endpoint-and-network-evidence/README.md)
- [Project 35: Develop An Incident Response Playbook And Tabletop](projects/35-develop-an-incident-response-playbook-and-tabletop/README.md)

## Advanced projects (36–50)
- [Project 36: Build A Dfir Evidence Collection Automation Pipeline](projects/36-build-a-dfir-evidence-collection-automation-pipeline/README.md)
- [Project 37: Create A Multi Source Incident Timeline With Plaso](projects/37-create-a-multi-source-incident-timeline-with-plaso/README.md)
- [Project 38: Perform Advanced Windows Memory Forensics](projects/38-perform-advanced-windows-memory-forensics/README.md)
- [Project 39: Investigate Lateral Movement Through Windows Artifacts](projects/39-investigate-lateral-movement-through-windows-artifacts/README.md)
- [Project 40: Reconstruct Credential Access Indicators From Logs And Memory](projects/40-reconstruct-credential-access-indicators-from-logs-and-memory/README.md)
- [Project 41: Analyze Linux Rootkit Indicators In A Forensic Image](projects/41-analyze-linux-rootkit-indicators-in-a-forensic-image/README.md)
- [Project 42: Investigate Container And Kubernetes Incident Artifacts](projects/42-investigate-container-and-kubernetes-incident-artifacts/README.md)
- [Project 43: Perform Cloud Incident Forensics For Aws](projects/43-perform-cloud-incident-forensics-for-aws/README.md)
- [Project 44: Perform Cloud Incident Forensics For Azure](projects/44-perform-cloud-incident-forensics-for-azure/README.md)
- [Project 45: Perform Cloud Incident Forensics For Gcp](projects/45-perform-cloud-incident-forensics-for-gcp/README.md)
- [Project 46: Build A Forensic Evidence Chain Of Custody System](projects/46-build-a-forensic-evidence-chain-of-custody-system/README.md)
- [Project 47: Create A Malware Incident Triage And Containment Workflow](projects/47-create-a-malware-incident-triage-and-containment-workflow/README.md)
- [Project 48: Investigate Data Exfiltration With Network And Endpoint Evidence](projects/48-investigate-data-exfiltration-with-network-and-endpoint-evidence/README.md)
- [Project 49: Run A Full Enterprise Incident Response Simulation](projects/49-run-a-full-enterprise-incident-response-simulation/README.md)
- [Project 50: Build An Enterprise Dfir Program And Reference Architecture](projects/50-build-an-enterprise-dfir-program-and-reference-architecture/README.md)

## Recommended references
- NIST SP 800-61, Computer Security Incident Handling Guide
- NIST SP 800-86, Guide to Integrating Forensic Techniques into Incident Response
- MITRE ATT&CK
- The Sleuth Kit and Autopsy documentation
- Volatility 3 documentation
- Plaso and Timesketch documentation
