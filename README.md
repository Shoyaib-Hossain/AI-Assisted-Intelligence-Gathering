# Methodology for AI-Assisted Intelligence Gathering

## Research Question (RQ1)

**To what extent can Large Language Models (LLMs) accurately extract structured Cyber Threat Intelligence (CTI) elements from unstructured threat reports across different use cases?**

This study defines six canonical CTI use cases, each operationalised through a clearly defined extraction schema.

---

## CTI Use Cases and Extraction Schema

| Use Case | What the LLM Should Extract | Example Sources |
|----------|----------------------------|----------------|
| **1. Vulnerability Intelligence Reports** | CVE, affected product, affected versions, fixed version, patch link, mitigation, evidence of exploitation | [Nginx UI vulnerability](https://intruceptlabs.com/2026/04/vulnerability-in-nginx-ui-webserver-allow-attackers-to-take-full-control-of-servers/) <br> [Snap LPE flaw](https://blog.qualys.com/vulnerabilities-threat-research/2026/03/17/cve-2026-3888-important-snap-flaw-enables-local-privilege-escalation-to-root) <br> [React Native CVE](https://www.averlon.ai/blog/vulnerability-intelligence-brief-cve-2025-11953-react-native-metro-command-injection) |
| **2. Malware Campaign Reports** | Malware family, file hashes, filenames, delivery method, behaviour, persistence, affected platform, detection/response actions | [OceanLotus PyPI campaign](https://securelist.com/oceanlotus-suspected-pypi-zichatbot-campaign/119603/) <br> [Cloud Atlas campaign](https://securelist.com/cloud-atlas-h1-2025-campaign/118517/) <br> [Booking.com phishing malware](https://www.microsoft.com/en-us/security/blog/2025/03/13/phishing-campaign-impersonates-booking-com-delivers-a-suite-of-credential-stealing-malware/) |
| **3. C2 / Network Infrastructure** | IPs, domains, URLs, ports, protocols, C2 framework, infrastructure pattern, firewall/DNS/proxy/SIEM checks | [CISA advisory](https://www.cisa.gov/news-events/cybersecurity-advisories/aa26-113a) <br> [Unit 42 Ivanti threat brief](https://unit42.paloaltonetworks.com/threat-brief-ivanti-cve-2025-0282-cve-2025-0283/) |
| **4. Phishing / Credential Theft** | Phishing domains, URLs, lure theme, impersonated brand, credential type, target sector, detection/response actions | [Microsoft phishing campaigns](https://www.microsoft.com/en-us/security/blog/2026/03/19/when-tax-season-becomes-cyberattack-season-phishing-and-malware-campaigns-using-tax-related-lures/) <br> [AiTM phishing campaign](https://www.microsoft.com/en-us/security/blog/2026/05/04/breaking-the-code-multi-stage-code-of-conduct-phishing-campaign-leads-to-aitm-token-compromise/) <br> [Google Threat Intel](https://cloud.google.com/blog/topics/threat-intelligence/unc6692-social-engineering-custom-malware) <br> [Cisco Talos campaign](https://blog.talosintelligence.com/spam-campaign-targeting-brazil-abuses-rmm-tools/) |
| **5. TTP / MITRE ATT&CK Mapping** | Adversary behaviour, ATT&CK tactics, techniques, sub-techniques, evidence, detection opportunities, mitigations | [UNC1549 analysis](https://cloud.google.com/blog/topics/threat-intelligence/analysis-of-unc1549-ttps-targeting-aerospace-defense) <br> [Qilin attack methods](https://blog.talosintelligence.com/uncovering-qilin-attack-methods-exposed-through-multiple-cases/) <br> [Talos UAT-8837](https://blog.talosintelligence.com/uat-8837/) |
| **6. Ransomware Incident Reports** | Initial access, ransomware family, affected assets, encryption/extortion behaviour, IOCs, containment, recovery, reporting actions | [CISA ransomware advisory](https://www.cisa.gov/news-events/cybersecurity-advisories/aa24-109a) <br> [State of ransomware 2026](https://securelist.com/state-of-ransomware-in-2026/119761/) <br> [CISA advisory](https://www.cisa.gov/news-events/cybersecurity-advisories/aa25-071a) |

---

## Summary

This framework establishes a structured approach for evaluating LLM performance across diverse CTI scenarios. Each use case reflects a distinct intelligence requirement, enabling systematic assessment of extraction accuracy, consistency, and completeness across heterogeneous threat reports.
