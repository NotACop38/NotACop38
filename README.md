# Tyler Graves

**Detection engineering · DFIR · Reverse engineering**

Boise, Idaho · [LinkedIn](https://www.linkedin.com/in/tyler-graves-security) · [Credentials](#credentials)

I build defensive security tools in Python and Rust. My work spans detection development, digital forensics and incident response, and binary analysis, with an emphasis on testable behavior and results an analyst can inspect.

## Selected projects

### Detection engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** converts Sigma rules to Splunk SPL and Microsoft Sentinel/Defender KQL. It tests detection logic against positive and negative synthetic fixtures and maps rules to MITRE ATT&CK and ATLAS.

**[PromptHound](https://github.com/NotACop38/PromptHound)** provides experimental Sigma detections for LLM applications and AI agents, including correlations grouped by tenant. It includes SPL/KQL query templates, telemetry normalization, offline regression tests, and mappings to OWASP LLM Top 10 and MITRE ATLAS.

**[SubStation](https://github.com/NotACop38/SubStation)** pairs Sigma and Zeek rules with synthetic PCAP and JSONL scenarios for testing industrial protocol detections. It covers Modbus, DNP3, and Siemens S7, with ATT&CK for ICS mappings.

### Digital forensics & incident response

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** analyzes `.eml` and `.msg` files offline, preserving indicator provenance and explaining its heuristic scores. Reports include defanged indicators and flag incomplete analysis. OSINT enrichment is optional.

**[Casebound](https://github.com/NotACop38/Casebound)** builds forensic timelines from host triage data. Its optional AI narrative layer checks citations and structured facts against the timeline and records rejected claims for review.

### Reverse engineering

**[Sextant](https://github.com/NotACop38/Sextant)** uses statistical analysis to propose binary layouts and measure how well they parse the input samples. Its offline Rust CLI exports supported layouts as editable Kaitai Struct definitions, ImHex patterns, Wireshark dissectors, and 010 Editor templates.

## Tools & languages

- **Detection & response:** Splunk Enterprise Security (SPL), Microsoft Sentinel (KQL), Microsoft Defender, Cortex XSOAR, Sigma.
- **Programming:** Python, Rust, PowerShell, C, x86 assembly.

## Credentials

- [**GASAE** · GIAC AI Security Automation Engineer](https://www.credly.com/badges/6d6e1209-86d2-4f20-9baa-c582cda7ca97)
- [**GCIH** · GIAC Certified Incident Handler](https://www.credly.com/badges/ab370d73-0529-4eb6-b8c9-c5e956928e2b)
- [**GSEC** · GIAC Security Essentials Certification](https://www.credly.com/badges/6ca3d309-d4db-4c88-9f33-c03faf5802ad)
- [**GFACT** · GIAC Foundational Cybersecurity Technologies](https://www.credly.com/badges/0c45243e-0307-43f4-8be4-bc48d9997773)

Member of the [GIAC Advisory Board](https://www.credly.com/badges/7c37c225-46ab-4ea6-b5db-d299f7020d91).
