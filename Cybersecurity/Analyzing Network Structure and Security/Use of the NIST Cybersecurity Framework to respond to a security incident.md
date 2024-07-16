# Incident Report Analysis  

- [Incident Report Analysis Template](https://docs.google.com/document/d/1EnieOKYJyKGsVff5Gg-3-dVwrHrZ2m8Hig6tVpfKqyg/template/preview?resourcekey=0-eb5t-d69zTPLEGthIpVlXw)

- [NIST Cybersecurity Framework ](https://docs.google.com/document/d/15yCDbDCOAcJw-LTz2DeCA7UeLRfvsf176T6MA6ku6ok/template/preview)  

## Incident Report
  ### Scenario 


<p align="justify"> As a cybersecurity analyst at our multimedia company, we recently experienced a DDoS attack that compromised our internal network for two hours. It was a challenging time as our network services suddenly stopped responding due to an influx of ICMP packets. This prevented normal internal network traffic from accessing any network resources. To mitigate the impact, our incident management team promptly blocked incoming ICMP packets, taking non-critical network services offline temporarily while restoring critical network services.
<p align="justify"> Following the attack, our dedicated cybersecurity team conducted a thorough investigation into the security event. Through their analysis, they discovered that a malicious actor had flooded our network with ICMP pings by exploiting an unconfigured firewall. This vulnerability allowed the attacker to execute a distributed denial of service (DDoS) attack, overwhelming our network resources.  

<p align="justify"> To address this security event and enhance our network security, our network security team implemented several crucial measures:
We implemented a new firewall rule to limit the rate of incoming ICMP packets, ensuring that future DDoS attacks would have a lesser impact on our network.
Source IP address verification was configured on the firewall to check for spoofed IP addresses on incoming ICMP packets. This step effectively prevents attackers from using falsified source IP addresses to bypass our security measures.  

<p align="justify"> We deployed network monitoring software to detect abnormal traffic patterns in real-time. This proactive approach allows us to identify potential DDoS attacks promptly and respond swiftly.
An IDS/IPS system was integrated to filter out suspicious ICMP traffic based on predefined rules and characteristics. This additional layer of protection helps in mitigating potential threats and ensuring the integrity of our network.  

<p align="justify"> As a dedicated cybersecurity analyst, it is now my responsibility to leverage the knowledge gained from this security event to develop a comprehensive plan to improve our company's network security. I will follow the guidelines provided by the National Institute of Standards and Technology (NIST) Cybersecurity Framework (CSF) to analyze this cybersecurity event thoroughly. By doing so, I will be able to integrate my analysis into a cohesive security strategy that aligns with industry best practices and safeguards our network infrastructure against future threats.


|         |            |
| ------------- |:-------------:|
| **Summary**      |<p align="justify"> A security issue occurred at the organisation when all network services abruptly ceased working. Through a barrage of incoming traffic, the cybersecurity team discovered that the outage was caused by a distributed denial of services (DDoS) attack.packets with ICMP. The group countered by thwarting the attack and suspending all non-essential network functions, allowing the restoration of vital network functions.</p>|
| **Identify**      |<p align="justify"> An ICMP flood attack was launched against the company by a malicious actor or actors. It impacted the whole internal network. It was necessary to secure and return all vital network resources to operational status.</p>      |
| **Protect** |<p align="justify"> The cybersecurity team put in place an IDS/IPS system to filter out certain ICMP traffic based on suspicious features and a new firewall rule to restrict the rate at which incoming ICMP packets could be sent. </p>     |
| **Detect** |<p align="justify"> The cybersecurity team installed network monitoring tools to identify unusual traffic patterns and set up source IP address verification on the firewall to check for spoofing IP addresses on incoming ICMP packets.</p>      |
| **Respond** |<p align="justify"> The cybersecurity team will isolate impacted systems in the case of future security incidents to stop additional network damage. They'll try to fix any vital services and systems that the incident interfered with. After that, the group will examine network logs to look for unusual or suspicious activity. All occurrences will also be reported by the team to higher management and, if necessary, the relevant legal authorities.</p>      |
| **Recover** |<p align="justify"> Restoring regular working network service access is necessary to recover from an ICMP flooding DDoS attack. It will be possible to stop external ICMP flood attacks at the firewall in the future. Then, in order to lessen internal network traffic, all non-essential network services had to be discontinued. The next step is to restore essential network services initially. Eventually, all non-critical network services and systems can be restored to their previous online states after the deluge of ICMP messages has timed out.</p>      |