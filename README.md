# Incident-report-analysis-lab


## Objective

Demostrate knowledge of incident report analysis and cybersecurity frameworks to assess network vulnerabilities, check the effectiveness of security controls, and create practical strategies to reduce risks. This involves following the NIST Cybersecurity Framework to identify, protect, detect, respond to, and recover from security incidents, aiming to make the organization more secure and improve how it handles incidents.

### Skills Learned

- Network Security Analysis
- Incident Response
- NIST Cybersecurity Framework Application
- Firewall Configuration
- Intrusion Detection and Prevention Systems (IDS/IPS)
- Data Backup and Recovery
- Security Tools and Software


## Applying the NIST CSF

There are five core functions of the NIST CSF framework: identify, protect, detect, respond, and recover.

These core functions help organizations manage cybersecurity risks, implement risk management strategies, and learn from previous mistakes. Plans based on this framework should be continuously updated to stay ahead of the latest security threats. The core functions help ensure organizations are protected against potential threats, risks, and vulnerabilities. Each function can be used to improve an organization’s security: 

- Identify: Manage security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
- Protect: Develop a strategy to protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
- Detect: Scan for potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- Respond: Ensure that the proper procedures are used to contain, neutralize and analyze security incidents and implement improvements to the security process.
- Recover: Return affected systems back to normal operation and restore systems data and assets that have been affected by an incident.

Some questions to ask for each of the five core functions, include:

| **Category**           | **Description**                                                                                                    |
|-----------------------|--------------------------------------------------------------------------------------------------------------------|
| **Identify**           | Perform regular audits of internal networks, systems, devices, and access privileges to find gaps. Identify risks through comprehensive assessments. **Technology/Asset Management**: Which hardware devices, operating systems, and software were affected? Trace the flow of the attack through the internal network. **Process/Business Environment**: Which business processes were affected in the attack? **People**: Who needs access to the affected systems? |
| **Protect**            | Implement policies, procedures, training, and tools to mitigate cybersecurity threats. Secure assets with proactive measures. **Access Control**: How are systems and data being protected? **Awareness Training**: What employee education is in place to reduce risk? **Protective Technology**: What tools or technologies are used to safeguard against threats? |
| **Detect**             | Monitor and improve detection capabilities for security incidents. Use advanced tools to identify threats quickly. **Anomalies and Events**: What indicators of compromise can be monitored? **Continuous Monitoring**: Are systems monitored for irregular activity? **Detection Processes**: Are there formal processes in place for detection? |
| **Respond**            | Contain, neutralize, and analyze incidents; implement process improvements. Provide thorough documentation of response actions. **Response Planning**: Is there a plan to address incidents? **Communication**: Who needs to be informed during an incident? **Mitigation**: How are threats being neutralized? **Improvements**: What lessons are learned and applied? |
| **Recover**            | Restore systems and data to normal operation after an incident. Develop a strategy to minimize downtime and future risks. **Recovery Planning**: How will affected systems and data be restored? **Improvements**: What measures will prevent future incidents? **Communication**: How are stakeholders updated during recovery? |


The NIST CSF and its five core functions provide a framework of planning proactive to applying reactive measures to cybersecurity threats. These functions are essential for ensuring that an organization has effective security strategies in place. An organization must have the ability to quickly recover from any damage caused by an incident to minimize their level of risk. 


## Scenario

As a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.
During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. 
The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 
The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

To address this security event, the network security team implemented: 
- A new firewall rule to limit the rate of incoming ICMP packets
- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets
- Network monitoring software to detect abnormal traffic patterns
- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

As a cybersecurity analyst, the task is using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

We have broken the analysis into different parts in the template below. You can explore them here:

- Identify security risks through regular audits of internal networks, systems, devices, and access privileges to identify potential gaps in security.
- Protect internal assets through the implementation of policies, procedures, training and tools that help mitigate cybersecurity threats.
- Detect potential security incidents and improve monitoring capabilities to increase the speed and efficiency of detections.
- Respond to contain, neutralize, and analyze security incidents; implement improvements to the security process.
- Recover affected systems to normal operation and restore systems data and/or assets that have been affected by an incident.



### Scope: 

### Goals: 

### Additional comments

## Recommendations
