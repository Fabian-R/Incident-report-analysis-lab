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


## Incident report

| Title       | Information |
|-------------|-------------|
| Summary     | The organization experienced a Distributed Denial of Service (DDoS) attack that disrupted internal network services for two hours. The attack exploited an unconfigured firewall, flooding the network with ICMP packets. Critical services were restored by blocking incoming ICMP traffic, shutting down non-critical services, and implementing new security measures. |
| Identify    | **Technology/Asset Management:** The attack targeted the company’s firewall and overwhelmed network resources with ICMP packets. The internal network was inaccessible, and critical services were disrupted. <br> **Process/Business Environment:** The attack impacted business processes reliant on network connectivity, such as web design and social media marketing services. <br> **People:** IT administrators, network security staff, and potentially affected employees required access to the compromised systems. |
| Protect     | **Access Control:** Implemented a new firewall rule to limit the rate of incoming ICMP packets. <br> **Awareness Training:** Employees were trained on identifying unusual activity and potential vulnerabilities. <br> **Protective Technology:** Deployed source IP address verification on the firewall and updated firewall configurations to prevent similar attacks. |
| Detect      | **Anomalies and Events:** Monitored incoming ICMP traffic for unusual patterns or high-volume requests. <br> **Continuous Monitoring:** Implemented network monitoring software to identify and flag abnormal traffic. <br> **Detection Processes:** Established protocols for monitoring and responding to ICMP-based threats. |
| Respond     | **Response Planning:** Blocked incoming ICMP packets and shut down non-critical network services to mitigate the impact. <br> **Communication:** Informed the cybersecurity team and upper management about the incident; prepared notifications for stakeholders if needed. <br> **Mitigation:** Neutralized the attack by adjusting firewall rules and restoring critical services. <br> **Improvements:** Documented the incident to refine future response protocols and improve network defenses. |
| Recover     | **Recovery Planning:** Restored affected network services and ensured critical systems were fully operational. <br> **Improvements:** Regular audits and updates to firewall configurations to prevent future DDoS attacks. <br> **Communication:** Updated management and relevant teams on the recovery status and ongoing improvements. |


## General Comments & Recommendations

- Root Cause Analysis: While the report identifies the unconfigured firewall as a vulnerability, further investigation is crucial.
- Vulnerability Scanning: Conduct regular vulnerability scans to identify and address potential weaknesses in the network infrastructure.
- Threat Intelligence: Utilize threat intelligence feeds to stay informed about emerging threats and vulnerabilities.
- Incident Response Testing: Tabletop Exercises: Regularly conduct tabletop exercises to test and refine incident response plans. Simulate DDoS attacks to evaluate the effectiveness of current procedures and identify areas for improvement.
- Penetration Testing: Engage a qualified security firm to conduct penetration testing to identify and exploit vulnerabilities in the network.
- Network Segmentation: Implement network segmentation to isolate critical systems and limit the impact of future attacks.
- DDoS Mitigation Services: Consider subscribing to a DDoS mitigation service to provide an additional layer of protection against future attacks. These services can help absorb and deflect malicious traffic before it reaches the organization's network.
- Employee Training: Phishing Simulations: Conduct regular phishing simulations to educate employees about social engineering tactics and the importance of cybersecurity best practices.
- Security Awareness: Emphasize the importance of strong passwords, avoiding suspicious links, and reporting any suspicious activity.
- Documentation: Document and analyze lessons learned from this incident to inform future security decisions and improve overall security posture.

### Key Takeaways:

This incident highlights the importance of proactive security measures, including regular vulnerability assessments, robust security controls, and ongoing employee training.
By implementing the recommendations above, the organization can significantly enhance its ability to prevent, detect, and respond to future cyber threats.
