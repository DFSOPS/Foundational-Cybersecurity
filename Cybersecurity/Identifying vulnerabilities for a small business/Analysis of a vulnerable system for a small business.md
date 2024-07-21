**Vulnerability Assessment Report**

**1<sup>st</sup> January 20XX**

# System Description

<p align="justify">128GB of memory and a potent CPU processor make up the server hardware. It has a MySQL database management system and is powered by the most recent version of the Linux operating system. It communicates with other servers on the network and is set up with a reliable IPv4 network connection. SSL/TLS encrypted connections are among the security precautions.

# Scope

This vulnerability assessment's scope is related to the system's present access controls. The evaluation will take place between June 20XX and August 20XX, a span of three months. The information system's risk analysis is guided by [NIST SP 800-30 Rev. 1](https://docs.google.com/document/d/1pRpdpQMEWskxSkwqEMv8W7A7x8GXQlcn0hEcDzWet3Y/template/preview?resourcekey=0-3GRRWAd8HryVgof-Jc33yA).

# Purpose

<p align="justify">Large volumes of data are managed and stored by a centralised computer system called the database server. In order to track results and tailor marketing campaigns, the server is utilised to store customer, campaign, and analytical data. Because the system is regularly used for marketing operations, security is essential.

# Risk Assessment    

| **Threat source** | **Threat event** | **Likelihood** | **Severity** | **Risk** |
| --- | --- | --- | --- | --- |
| _Hacker_ | _Obtain sensitive information via exfiltration_ | _3_ | _3_ | _9_ |
| --- | --- | --- | --- | --- |
| _Employee_ | _Disrupt mission-critical operations_ | _2_ | _3_ | _6_ |
| --- | --- | --- | --- | --- |
| _Customer_ | _Alter/Delete critical information_ | _1_ | _3_ | _3_ |
| --- | --- | --- | --- | --- |

# Approach

<p align="justify">The business's data storage and management practices were taken into account while measuring risks. Based on the possibility of a security incident considering the information system's open access rights, potential threat sources and events were identified. The impact on regular operational requirements was considered in relation to the seriousness of prospective incidents.

# Remediation Strategy

<p align="justify">The database server is protected against unauthorised user access by the implementation of audits, authentication, and permission measures. Role-based access controls, multi-factor authentication, and strong passwords are some examples of how to restrict user privileges. Data in motion encryption employing TLS rather than SSL. Corporate offices can block arbitrary internet users from connecting to the database by implementing IP allow-listing.