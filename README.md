Project 1: Incident Response Playbooks 

Focus: SOC Operations, Threat Containment, and Recovery.

Overview: Developed comprehensive Incident Response Playbooks for Shuttlers Metropolitan Mobility Company. The goal was to standardize the detection, containment, and eradication of high-risk cyber threats to minimize business downtime.

Scenarios Covered:

Email Phishing: A simulated attack where the Billing Department was impersonated to steal credentials.

Response: Blocked sender domain, purged malicious emails, and blacklisted the URL.

Ransomware: A finance employee downloaded a fake update, leading to file encryption.

Response: Immediate network isolation (EDR), system wipe, and restoration from offline backups.

DDoS Attack: A botnet flooded the booking API with 20Gbps of traffic.

Response: Implemented Geo-blocking (blocking non-local traffic) and Rate Limiting via WAF.