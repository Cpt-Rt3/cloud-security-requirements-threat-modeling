# Cloud Security Requirements & Threat Modeling

## Project Summary
(you already wrote this — keep it)

## Threat Model
## Threat Model Architecture

![Acme Everything Smart – Threat Model Architecture](screenshots/Acme-everything-smart-threat-model-architecture.png)

This architecture diagram illustrates the threat entry points, trust boundaries, control layers, and monitoring flow for the Acme Everything Smart SaaS IoT platform. It demonstrates how identity, encryption, vulnerability management, logging, and optional deception techniques work together to detect, contain, and respond to threats across the cloud application lifecycle.

### Primary Risks
### Threat Actors
### Assumptions

## Environment Setup
### Cloud Platform Assumptions
### Identity & Access
### Logging & Monitoring

## Implementation & Analysis
(How you mapped risks → CCM controls)

## How to Run This Yourself
1. Review architecture assumptions
2. Identify assets and trust boundaries
3. Map threats to CCM control families
4. Document gaps and recommendations

## Results & Evidence
This is not about logs or screenshots (unless you want to add them later).

It’s about outcomes:

High-risk areas identified (identity misuse, API abuse, data exfil)

Gaps acknowledged (no real SIEM integration, conceptual tooling)

Security posture: defense-in-depth with monitoring maturity

## Executive Summary
The platform assumes hostile networks by default

Identity is the primary control plane

Visibility closes the loop between prevention and response

Architecture favors detection and containment over perfection

## Tools Used
- Cloud Controls Matrix (CCM)
- Azure (assumed)
- SIEM (Splunk – conceptual)
- Identity Provider (Okta – conceptual)

Threat identification and control mapping in this project align with CSA CCM domains and NIST SP 800-series guidance, informed by ATT&CK threat behaviors and OWASP risk patterns.

## References

- Cloud Security Alliance. (2021). *Cloud Controls Matrix (CCM) v4*.  
  https://cloudsecurityalliance.org/research/cloud-controls-matrix

- National Institute of Standards and Technology. (2020).  
  *Security and Privacy Controls for Information Systems and Organizations (SP 800-53 Rev. 5).*  
  https://doi.org/10.6028/NIST.SP.800-53r5

- National Institute of Standards and Technology. (2018).  
  *Framework for Improving Critical Infrastructure Cybersecurity (NIST CSF).*  
  https://www.nist.gov/cyberframework

- MITRE Corporation. (2023).  
  *MITRE ATT&CK® Framework.*  
  https://attack.mitre.org/

- OWASP Foundation. (2021).  
  *OWASP Top 10 Web Application Security Risks.*  
  https://owasp.org/www-project-top-ten/


## Closing Note

This project demonstrates a security-first mindset grounded in practical threat modeling and control mapping. While Acme Everything Smart is fictional, the risks, controls, and architectural patterns reflect real-world cloud security challenges faced by modern SaaS and IoT platforms.

- Cloud Security Alliance – CCM
- NIST SP 800-series
