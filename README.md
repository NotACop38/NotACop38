<h1 align="center">Tyler Graves</h1>

<p align="center">
  Reverse engineering, malware research, and detection tooling.
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

<p align="center"><img src="assets/divider.svg" width="100%" height="8" alt=""></p>

I'm drawn to the low level: reverse engineering, malware development, and building tools that turn raw signal into something a person can act on. Most of what I make is aimed at researchers and small security teams, the people doing real work without a vendor's budget behind them. The open-source projects below grow out of that, taking inputs like network captures, mail headers, unknown binaries, and AI-agent logs and turning them into something you can test, verify, and use.

### Selected Work

#### Detection Engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** compiles Sigma rules into Splunk SPL and Microsoft Sentinel KQL, fire-tests each one in CI, and maps coverage to MITRE ATT&CK and ATLAS. It ships with a dedicated detection pack for LLM and AI-app threats.
<br><sub>`Python` &middot; `Sigma` &middot; `Splunk SPL` &middot; `Sentinel KQL` &middot; `CI`</sub>

**[PromptHound](https://github.com/NotACop38/PromptHound)** is a SIEM-ready detection library for attacks against LLM apps and AI agents. Sigma rules convert to SPL and KQL, mapped to the OWASP LLM Top 10 and MITRE ATLAS, with a synthetic telemetry generator that exercises every rule offline.
<br><sub>`Python` &middot; `OWASP LLM Top 10` &middot; `MITRE ATLAS` &middot; `detection-as-code`</sub>

**[SubStation](https://github.com/NotACop38/SubStation)** is detection content for industrial-protocol attacks (Modbus, DNP3, Siemens S7), mapped to MITRE ATT&CK for ICS. A bundled traffic simulator emits benign and anomalous telemetry as PCAP and JSON, so OT detections validate without a PLC or live hardware.
<br><sub>`Python` &middot; `Modbus / DNP3 / S7` &middot; `ATT&CK for ICS` &middot; `PCAP`</sub>

#### Digital Forensics &amp; Incident Response

**[Casebound](https://github.com/NotACop38/Casebound)** is a local-first DFIR copilot that assembles a verified forensic timeline and an evidence-grounded narrative. Every AI claim has to cite a real event or it is rejected, so the report carries no invented findings.
<br><sub>`DFIR` &middot; `local-first` &middot; `timeline analysis` &middot; `evidence-grounded AI`</sub>

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** is a self-hostable phishing-triage tool. It parses a suspicious `.eml` or `.msg`, defangs IOCs, enriches them via OSINT, and produces a transparent risk score with an analyst-ready report. Nothing is sent, opened, or detonated, so triage stays safe by construction.
<br><sub>`Python` &middot; `email forensics` &middot; `OSINT` &middot; `IOC enrichment`</sub>

#### Reverse Engineering &amp; Tooling

**[Sextant](https://github.com/NotACop38/Sextant)** is a Rust CLI that infers the structure of unknown binary formats and network protocols from sample files, then generates verified parsers for Kaitai Struct, ImHex, Wireshark (Lua dissector), and 010 Editor, plus an annotated field map and confidence report. A native Rust execution engine drives a generate-test-refine loop that accepts an LLM proposal only when the verified parse score actually improves.
<br><sub>`Rust` &middot; `binary analysis` &middot; `protocol RE` &middot; `parser generation`</sub>

<p align="center"><img src="assets/divider.svg" width="100%" height="8" alt=""></p>

<p align="center">
  <sub>
    <b>Detection &amp; SIEM</b>&nbsp;&nbsp;Splunk Enterprise Security (SPL) &middot; Microsoft Sentinel (KQL) &middot; Microsoft Defender &middot; Sigma<br>
    <b>Automation &amp; SOAR</b>&nbsp;&nbsp;Cortex XSOAR &middot; Python &middot; PowerShell<br>
    <b>Languages</b>&nbsp;&nbsp;Python &middot; PowerShell &middot; Rust &middot; C &middot; Assembly (Intel x86)<br>
    <b>Frameworks &amp; Taxonomies</b>&nbsp;&nbsp;MITRE ATT&amp;CK &middot; MITRE ATLAS &middot; ATT&amp;CK for ICS &middot; OWASP LLM Top 10
  </sub>
</p>

<p align="center">
  <sub>Each project ships with its own way to check the output: rules tested in CI, synthetic telemetry, validation against real samples, reports you can audit.</sub>
</p>
