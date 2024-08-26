# Performing Incident Response and Forensic Analysis

**Author**: Osamudiamen Eweka  
**Course**: CYB-605-Z2 Principles of Cybersecurity  
**Institution**: Utica University

## Overview

This lab explores the critical processes of incident response and forensic analysis, providing hands-on experience in investigating cybersecurity incidents. Participants engage in analyzing network traffic (PCAP files) and disk images using tools like NetWitness Investigator and Autopsy to uncover evidence related to a security breach. The exercises emphasize preserving evidence integrity, constructing incident timelines, and creating detailed incident response reports.

## Objectives

- Understand the phases of incident response: preparation, detection, analysis, containment, eradication, recovery, and post-incident analysis.
- Use forensic tools like NetWitness Investigator and Autopsy to analyze PCAP files and disk images.
- Identify and correlate evidence across different sources to build a comprehensive narrative of the cybersecurity incident.
- Develop a detailed incident response report, documenting the investigative process, findings, and recommendations.

## Lab Setup

### Lab Environment Details

The lab requires the following software tools:

- **NetWitness Investigator**: A network forensic analysis tool used to examine PCAP files.
- **Autopsy**: A digital forensics platform used for analyzing disk images.
  
These tools enable participants to analyze network traffic and disk images, uncovering critical evidence that informs their incident response strategies.

## Hands-On Demonstrations

### 1. Analyze a PCAP File for Forensic Evidence
Participants used NetWitness Investigator to analyze a PCAP file related to a security breach at Giggly Goofo on July 31, 2021. This analysis uncovered suspicious network activities, including FTP transfers of .zip files and a suspicious `clickme.exe` file. A key finding was the identification of a malicious external IP address involved in the data exfiltration.

### 2. Analyze a Disk Image for Forensic Evidence
Participants employed Autopsy to analyze the disk image from Marvin Jonson's laptop, a suspected insider. The investigation revealed an email containing FTP credentials sent from Marvin's account to an external actor, Dr. Evil, raising concerns about his involvement in the breach.

### 3. Incident Response Report and Analysis
Participants created a detailed incident response report documenting their findings from the forensic analysis. The report outlined the timeline of events, identified compromised systems, and provided recommendations for mitigating the impact of the breach and preventing future incidents.

## Challenge and Analysis

### 1. Identify Additional Email Evidence
Further analysis of Marvin Jonson’s email communications revealed additional malicious activities, including instructions to install a keylogger and tamper with firewall configurations. These findings expanded the scope of the incident, indicating ongoing unauthorized access and surveillance within the company’s network.

### 2. Identify Evidence of Spyware
Participants investigated Marvin's workstation for evidence of spyware installation. Autopsy revealed the presence of a keylogger scheduled in the system’s `Tasks` directory, confirming the installation and activation of unauthorized surveillance software.

## Conclusion

This lab provided a comprehensive exploration of incident response and forensic analysis techniques. Participants gained practical skills in identifying, correlating, and documenting evidence across multiple sources, preparing them to handle real-world cybersecurity incidents. The exercises emphasized the importance of thorough forensic investigations and detailed incident response reporting to safeguard organizations against cyber threats.

## References

- Grispos, G. (2015). *Security Incident Response Criteria: A Practitioner’s Perspective*. arXiv.org. https://arxiv.org/abs/1508.02526
- Jones & Bartlett (2024). *Performing Incident Response and Forensic Analysis (Figures)*. Jones and Bartlett Learning Virtual Lab. URL: https://jbl-lti.hatsize.com/startlab

For a complete list of references, please refer to the full lab report.
