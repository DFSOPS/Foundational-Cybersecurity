# Incident Report Analysis  

- [Incident Report Analysis Template](https://docs.google.com/document/d/1EnieOKYJyKGsVff5Gg-3-dVwrHrZ2m8Hig6tVpfKqyg/template/preview?resourcekey=0-eb5t-d69zTPLEGthIpVlXw)

- [NIST Cybersecurity Framework ](https://docs.google.com/document/d/15yCDbDCOAcJw-LTz2DeCA7UeLRfvsf176T6MA6ku6ok/template/preview)  

## Incident Report
  ### Scenario 


<p align="justify"> You are a cybersecurity analyst working for a multimedia company that offers web design services, graphic design, and social media marketing solutions to small businesses. Your organization recently experienced a DDoS attack, which compromised the internal network for two hours until it was resolved.

<p align="justify"> During the attack, your organization’s network services suddenly stopped responding due to an incoming flood of ICMP packets. Normal internal network traffic could not access any network resources. The incident management team responded by blocking incoming ICMP packets, stopping all non-critical network services offline, and restoring critical network services. 

<p align="justify"> The company’s cybersecurity team then investigated the security event. They found that a malicious actor had sent a flood of ICMP pings into the company’s network through an unconfigured firewall. This vulnerability allowed the malicious attacker to overwhelm the company’s network through a distributed denial of service (DDoS) attack. 

- To address this security event, the network security team implemented: 

- A new firewall rule to limit the rate of incoming ICMP packets

- Source IP address verification on the firewall to check for spoofed IP addresses on incoming ICMP packets

- Network monitoring software to detect abnormal traffic patterns

- An IDS/IPS system to filter out some ICMP traffic based on suspicious characteristics

<p align="justify"> As a cybersecurity analyst, you are tasked with using this security event to create a plan to improve your company’s network security, following the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF). You will use the CSF to help you navigate through the different steps of analyzing this cybersecurity event and integrate your analysis into a general security strategy. 

|         |            |
| ------------- |:-------------:|
| **Summary**      |<p align="justify"> A security issue occurred at the organisation when all network services abruptly ceased working. Through a barrage of incoming traffic, the cybersecurity team discovered that the outage was caused by a distributed denial of services (DDoS) attack.packets with ICMP. The group countered by thwarting the attack and suspending all non-essential network functions, allowing the restoration of vital network functions.</p>|
| **Identify**      |<p align="justify"> An ICMP flood attack was launched against the company by a malicious actor or actors. It impacted the whole internal network. It was necessary to secure and return all vital network resources to operational status.</p>      |
| **Protect** |<p align="justify"> The cybersecurity team put in place an IDS/IPS system to filter out certain ICMP traffic based on suspicious features and a new firewall rule to restrict the rate at which incoming ICMP packets could be sent. </p>     |
| **Detect** |<p align="justify"> The cybersecurity team installed network monitoring tools to identify unusual traffic patterns and set up source IP address verification on the firewall to check for spoofing IP addresses on incoming ICMP packets.</p>      |
| **Respond** |<p align="justify"> The cybersecurity team will isolate impacted systems in the case of future security incidents to stop additional network damage. They'll try to fix any vital services and systems that the incident interfered with. After that, the group will examine network logs to look for unusual or suspicious activity. All occurrences will also be reported by the team to higher management and, if necessary, the relevant legal authorities.</p>      |
| **Recover** |<p align="justify"> Restoring regular working network service access is necessary to recover from an ICMP flooding DDoS attack. It will be possible to stop external ICMP flood attacks at the firewall in the future. Then, in order to lessen internal network traffic, all non-essential network services had to be discontinued. The next step is to restore essential network services initially. Eventually, all non-critical network services and systems can be restored to their previous online states after the deluge of ICMP messages has timed out.</p>      |