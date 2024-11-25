# Incident-Response-Using-the-NIST-Cybersecurity-Framework

In this project, I led the incident response to a Distributed Denial of Service (DDoS) attack targeting the multimedia company, which offers web design, graphic design, and social media marketing services to small businesses. The attack compromised the internal network for approximately two hours, disrupting normal operations.

# Incident Overview
During the attack, the company's network services became unresponsive due to a flood of incoming ICMP (Internet Control Message Protocol) packets. This flood of traffic overwhelmed the network, preventing normal internal communication and access to critical resources. As a result, our team experienced significant disruptions in day-to-day operations, with internal users unable to access network services.


Network Security Improvement Plan Using the NIST Cybersecurity Framework (CSF)
In response to the DDoS attack, I’ve developed a network security improvement plan for the company, leveraging the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). This plan will help improve the company’s cybersecurity posture through a structured, proactive, and reactive approach. The NIST CSF's five core functions—Identify, Protect, Detect, Respond, and Recover—will guide the steps in fortifying the network and systems against future security events.

# Identify: Identify and Assess Security Risks
The first step is to identify potential security risks by conducting regular audits of internal networks, systems, devices, and access privileges to ensure that vulnerabilities are identified before they can be exploited.

Action Steps:

* Regular Audits: Implement regular vulnerability assessments and penetration testing to identify weaknesses in the network infrastructure, such as unconfigured firewalls, outdated software, or exposed services.
* Asset Inventory: Maintain an up-to-date inventory of all network devices and systems, classifying them based on their criticality to the business. This ensures better visibility into areas that need additional protection.
* Access Control Reviews: Review and manage user access privileges through role-based access controls (RBAC) to limit unnecessary exposure of sensitive systems.
* Third-party Risk Management: Evaluate the security posture of third-party services and partners to ensure that external sources do not introduce security risks.

# Protect: Implement Protective Measures
To prevent future incidents, the company needs to implement a series of policies, procedures, tools, and employee training programs designed to protect its assets from cyber threats.

Action Steps:

* Firewall Configuration: Ensure that all firewalls are properly configured, with specific rules to block malicious traffic, such as limiting the rate of incoming ICMP packets and verifying source IP addresses to prevent spoofing.
* Access Controls and Authentication: Strengthen access management by implementing multi-factor authentication (MFA) for all critical systems and accounts.
* Endpoint Protection: Deploy advanced endpoint protection software across all devices in the organization to detect and prevent malicious activity.
* Security Awareness Training: Conduct regular security training for employees to raise awareness about social engineering tactics, phishing, and best practices for securing company data.
* Patch Management: Implement a robust patch management process to ensure that all systems are updated with the latest security patches in a timely manner.

#  Detect: Improve Detection Capabilities
Detecting security incidents promptly is crucial to minimizing damage. This requires advanced monitoring tools and processes to identify abnormal traffic patterns and suspicious behavior.

Action Steps:

* Network Monitoring Tools: Deploy network monitoring software that provides visibility into traffic patterns, allowing for the early detection of abnormal activities such as a sudden spike in ICMP traffic.
* Intrusion Detection/Prevention Systems (IDS/IPS): Utilize IDS/IPS systems to automatically detect and filter out malicious ICMP traffic based on known attack signatures and suspicious characteristics.
* Anomaly Detection: Integrate machine learning-based tools that can analyze traffic patterns over time and identify deviations from normal behavior, allowing for faster detection of zero-day or new types of attacks.
* Log Management and SIEM: Implement a Security Information and Event Management (SIEM) system that aggregates logs from various network devices and security tools, enabling quicker identification of anomalies and incidents.

# Respond: Effectively Respond to Security Incidents
Once an incident is detected, the next priority is to contain, neutralize, and analyze the event to prevent further damage and learn from the attack.

Action Steps:

* Incident Response Plan: Develop and regularly update an incident response plan (IRP) to outline steps to take during various types of security incidents, including DDoS attacks. This plan should detail escalation procedures, communication protocols, and key personnel roles.
* Immediate Containment: In the event of a DDoS attack or other security event, immediately implement mitigating actions such as blocking malicious traffic, isolating compromised systems, and shutting down non-critical network services.
* Root Cause Analysis: After containing the incident, perform a thorough forensic investigation to determine the source and nature of the attack. This could involve analyzing traffic patterns, system logs, and the methods used to exploit vulnerabilities.
* Post-Incident Review: Conduct a post-incident review with all stakeholders to evaluate the effectiveness of the response, identify weaknesses in the process, and implement improvements to the security process.

# Recover: Restore Systems and Learn from the Incident
Once the threat has been neutralized, focus on recovery by restoring systems to normal operation and learning from the incident to prevent future occurrences.

Action Steps:

* System Restoration: Use clean backups to restore affected systems and data to their pre-incident state, ensuring that all compromised systems are fully sanitized before being reconnected to the network.
* Security Patches and Hardening: Apply all necessary security patches to systems and update firewall rules to block future DDoS traffic. Ensure that any discovered vulnerabilities are addressed to prevent similar attacks.
* Continuous Monitoring: After recovery, implement additional monitoring to ensure that the threat has been fully eradicated, and systems remain secure.
* Review and Update Policies: Update security policies, procedures, and tools based on lessons learned from the incident. This includes refining the firewall rules, IDS/IPS configurations, and incident response protocols to make them more effective in the future.
* Employee Training: Conduct additional training sessions for staff on the updated security measures and any new threats identified during the incident.

##  Technologies Used
- **Firewall Configuration**
- **Intrusion Detection and Prevention Systems (IDS/IPS)**
- **Network Monitoring Software**
- **Security Information and Event Management (SIEM)**
- **Incident Response Tools**
