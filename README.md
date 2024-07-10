# Incident-Report-Analysis-DDoS-Attack-Mitigation

## Project Overview

This project involves analyzing a DDoS attack incident at a multimedia company, applying the NIST Cybersecurity Framework (CSF) to identify and address the security vulnerabilities, and developing a comprehensive plan to improve the company's network security. The incident was resolved by implementing new security measures to prevent future attacks.

## Scenario

You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 
- A new firewall rule to limit the rate of incoming ICMP packets
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy.

## Project Scope and Goals

Scope: 
The project focuses on the identification, protection, detection, response, and recovery aspects of the NIST CSF in relation to the DDoS attack.

Goals:
- Analyze the DDoS attack and identify the security vulnerabilities exploited.
- Develop and implement measures to protect against similar future attacks.
- Improve detection capabilities to identify potential threats early.
- Establish a response plan to effectively address future incidents.
- Enhance recovery procedures to minimize downtime and data loss.

## Skills Learned

- Incident Response: Gained experience in managing and mitigating DDoS attacks.
- Network Security: Enhanced understanding of firewall configurations and network traffic monitoring.
- NIST Cybersecurity Framework: Applied the NIST CSF to a real-world scenario, improving security planning and strategy.
- Communication: Improved ability to communicate security incidents and recovery plans to stakeholders.
- Continuous Improvement: Learned the importance of regular security audits and updates to maintain a robust security posture.

## Tools Used

- Google Docs for recording my findings and documenting the Incident Report Analysis.

## Steps

1. Summary:
- Documented the DDoS attack and its impact on network services.
- Identified the unconfigured firewall as the vulnerability exploited.

2. Identify:
- Conducted an audit of systems, devices, and access policies.
- Traced the flow of the attack and identified affected business processes and personnel.

3. Protect:
- Implemented firewall rules to limit ICMP packet rates and verify source IP addresses.
- Provided employee training on security best practices.
- Updated firewall configurations and implemented an IPS.

4. Detect:
- Utilized firewall logging tools and IDS to monitor incoming traffic.
- Enhanced detection processes to identify and alert on anomalies.

5. Respond:
- Disabled compromised accounts and communicated response procedures.
- Analyzed the attack to refine response strategies.
- Implemented measures to mitigate the impact and isolate affected resources.

6. Recover:
- Restored network services and reconfigured security measures.
- Improved recovery processes to ensure swift restoration in future incidents.
- Communicated restoration procedures to stakeholders.

