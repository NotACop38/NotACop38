# Tyler Graves

**Detection engineering · DFIR · Reverse engineering**

Boise, Idaho · [LinkedIn](https://www.linkedin.com/in/tyler-graves-security) · [Credentials](#credentials)

I build defensive security tools in Python and Rust, focused on detection testing, forensic triage, and binary analysis.

## Selected projects

### Detection engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** combines Sigma rule authoring, query conversion, and synthetic regression tests for Windows and AI application logs. It targets Splunk SPL and Microsoft Sentinel/Defender KQL, with MITRE ATT&CK and ATLAS mappings.

**[PromptHound](https://github.com/NotACop38/PromptHound)** provides experimental Sigma detections for LLM applications and AI agents, with correlations grouped by tenant. It includes a versioned telemetry schema, SPL/KQL query templates, offline fixture tests, and OWASP LLM Top 10 and MITRE ATLAS mappings.

**[SubStation](https://github.com/NotACop38/SubStation)** pairs Sigma and Zeek rules with synthetic Modbus, DNP3, and Siemens S7 traffic for offline detection testing. It produces PCAP/JSONL artifacts, supports configurable site policies, and checks modeled fields against independent parsers.

### Digital forensics & incident response

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** analyzes `.eml` and `.msg` files offline and produces reports with defanged indicators, evidence sources, and explainable heuristic scores. It flags incomplete analysis and supports optional OSINT enrichment.

**[Casebound](https://github.com/NotACop38/Casebound)** normalizes host triage data into forensic timelines with source references and ATT&CK mappings. Its optional AI summaries render checked fields from cited events and include an audit of rejected claims.

### Reverse engineering

**[Sextant](https://github.com/NotACop38/Sextant)** explores binary formats through statistical inference in an offline Rust CLI. It tests candidate layouts against sample bytes and exports supported structures as editable Kaitai Struct definitions, ImHex patterns, Wireshark Lua dissectors, and 010 Editor templates.

## Tools & languages

- **Detection & response:** Splunk Enterprise Security (SPL), Microsoft Sentinel (KQL), Microsoft Defender, Cortex XSOAR, Sigma.
- **Programming:** Python, Rust, PowerShell, C, x86 assembly.

## Credentials

- [**GASAE** · GIAC AI Security Automation Engineer](https://www.credly.com/badges/6d6e1209-86d2-4f20-9baa-c582cda7ca97)
- [**GCIH** · GIAC Certified Incident Handler](https://www.credly.com/badges/ab370d73-0529-4eb6-b8c9-c5e956928e2b)
- [**GSEC** · GIAC Security Essentials Certification](https://www.credly.com/badges/6ca3d309-d4db-4c88-9f33-c03faf5802ad)
- [**GFACT** · GIAC Foundational Cybersecurity Technologies](https://www.credly.com/badges/0c45243e-0307-43f4-8be4-bc48d9997773)

Member of the [GIAC Advisory Board](https://www.credly.com/badges/7c37c225-46ab-4ea6-b5db-d299f7020d91).
