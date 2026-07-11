<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/header-light.svg">
    <img src="assets/header-light.svg" width="100%" alt="Tyler Graves: Detection Engineering · DFIR · Reverse Engineering">
  </picture>
</p>

<p align="center">
  Defensive security tooling you can verify, built for researchers and small teams.
</p>

<p align="center">
  Boise, Idaho &nbsp;&middot;&nbsp;
  <a href="https://www.linkedin.com/in/tyler-graves-security">LinkedIn</a>
</p>

<p align="center">
  <a href="https://www.credly.com/badges/0c45243e-0307-43f4-8be4-bc48d9997773" title="Verify on Credly"><img alt="GIAC GFACT" src="https://img.shields.io/badge/GIAC-GFACT-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/6ca3d309-d4db-4c88-9f33-c03faf5802ad" title="Verify on Credly"><img alt="GIAC GSEC" src="https://img.shields.io/badge/GIAC-GSEC-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/ab370d73-0529-4eb6-b8c9-c5e956928e2b" title="Verify on Credly"><img alt="GIAC GCIH" src="https://img.shields.io/badge/GIAC-GCIH-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/cec03649-509f-4dc2-bf07-5e4670fd1a65" title="Verify on Credly"><img alt="GIAC Advisory Board" src="https://img.shields.io/badge/GIAC-Advisory%20Board-334155?style=flat-square&labelColor=2B2B2B"></a>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/divider-light.svg">
    <img src="assets/divider-light.svg" width="100%" height="8" alt="">
  </picture>
</p>

I work close to the metal: reverse engineering, malware analysis, and detection engineering. The projects here turn raw signal (packet captures, mail headers, unknown binaries, AI-agent logs) into something an analyst can act on. They're built for researchers and small security teams without a vendor budget behind them, and each one includes a way to verify its output instead of trusting it.

### Projects

#### Detection Engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** compiles Sigma rules into Splunk SPL and Microsoft Sentinel KQL, fire-tests each rule in CI, and maps coverage to MITRE ATT&CK and ATLAS. There's also a detection pack for LLM and AI-app threats.
<br><sub>`Python` &middot; `Sigma` &middot; `Splunk SPL` &middot; `Sentinel KQL` &middot; `CI`</sub>

**[PromptHound](https://github.com/NotACop38/PromptHound)** is a detection library for attacks on LLM apps and AI agents, written to drop into a SIEM. The Sigma rules convert to SPL and KQL, map to the OWASP LLM Top 10 and MITRE ATLAS, and come with a synthetic telemetry generator that exercises every rule offline.
<br><sub>`Python` &middot; `OWASP LLM Top 10` &middot; `MITRE ATLAS` &middot; `detection-as-code`</sub>

**[SubStation](https://github.com/NotACop38/SubStation)** is detection content for industrial-protocol attacks (Modbus, DNP3, Siemens S7), mapped to MITRE ATT&CK for ICS. A bundled traffic simulator emits benign and anomalous telemetry as PCAP and JSON, so you can test OT detections without a PLC or live hardware.
<br><sub>`Python` &middot; `Modbus / DNP3 / S7` &middot; `ATT&CK for ICS` &middot; `PCAP`</sub>

#### Digital Forensics &amp; Incident Response

**[Casebound](https://github.com/NotACop38/Casebound)** is a local-first DFIR assistant that builds a verified forensic timeline and writes the case narrative from it. Every AI claim has to cite a real event or it gets rejected, so nothing in the report is invented.
<br><sub>`DFIR` &middot; `local-first` &middot; `timeline analysis` &middot; `evidence-grounded AI`</sub>

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** is a self-hosted phishing triage tool. It parses a suspicious `.eml` or `.msg`, defangs the IOCs, enriches them with OSINT, and writes a report with a risk score you can trace back to the evidence. Nothing gets sent, opened, or detonated.
<br><sub>`Python` &middot; `email forensics` &middot; `OSINT` &middot; `IOC enrichment`</sub>

#### Reverse Engineering &amp; Tooling

**[Sextant](https://github.com/NotACop38/Sextant)** is a Rust CLI that works out the structure of unknown binary formats and network protocols from sample files, then generates parsers for Kaitai Struct, ImHex, Wireshark (Lua dissector), and 010 Editor, plus an annotated field map and a confidence report. The Rust engine tests every LLM-proposed refinement against the samples and keeps it only if the parse score improves.
<br><sub>`Rust` &middot; `binary analysis` &middot; `protocol RE` &middot; `parser generation`</sub>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/divider-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="assets/divider-light.svg">
    <img src="assets/divider-light.svg" width="100%" height="8" alt="">
  </picture>
</p>

<p align="center">
  <sub>
    <b>Detection &amp; SIEM</b>&nbsp;&nbsp;Splunk Enterprise Security (SPL) &middot; Microsoft Sentinel (KQL) &middot; Microsoft Defender &middot; Sigma<br>
    <b>Automation &amp; SOAR</b>&nbsp;&nbsp;Cortex XSOAR &middot; Python &middot; PowerShell<br>
    <b>Languages</b>&nbsp;&nbsp;Rust &middot; C &middot; x86 Assembly &middot; Python &middot; PowerShell<br>
    <b>Frameworks &amp; Taxonomies</b>&nbsp;&nbsp;MITRE ATT&amp;CK &middot; MITRE ATLAS &middot; ATT&amp;CK for ICS &middot; OWASP LLM Top 10
  </sub>
</p>

<p align="center">
  <sub>Each project has its own way to check the output: rules fire-tested in CI, synthetic telemetry, validation against real samples, and reports you can audit.</sub>
</p>
