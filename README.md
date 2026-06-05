<h1 align="center">Tyler Graves</h1>

<p align="center">
  <em>Detection engineering &middot; digital forensics &amp; incident response &middot; reverse engineering</em>
</p>

<p align="center">
  Boise, Idaho
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tyler-graves-security">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:redacted">Email</a>
</p>

<p align="center">
  <a href="https://www.credly.com/badges/0c45243e-0307-43f4-8be4-bc48d9997773/linked_in_profile" title="Verify on Credly"><img alt="GIAC GFACT" src="https://img.shields.io/badge/GIAC-GFACT-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/6ca3d309-d4db-4c88-9f33-c03faf5802ad/linked_in_profile" title="Verify on Credly"><img alt="GIAC GSEC" src="https://img.shields.io/badge/GIAC-GSEC-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/ab370d73-0529-4eb6-b8c9-c5e956928e2b/linked_in_profile" title="Verify on Credly"><img alt="GIAC GCIH" src="https://img.shields.io/badge/GIAC-GCIH-8A1538?style=flat-square&labelColor=2B2B2B"></a>
  <a href="https://www.credly.com/badges/cec03649-509f-4dc2-bf07-5e4670fd1a65/linked_in_profile" title="Verify on Credly"><img alt="GIAC Advisory Board" src="https://img.shields.io/badge/GIAC-Advisory%20Board-334155?style=flat-square&labelColor=2B2B2B"></a>
</p>

<p align="center"><img src="assets/divider.svg" width="100%" height="8" alt=""></p>

### Selected Work

<sub>A through-line across the work: take messy, real-world signal — network captures, mail headers, raw binaries, AI-agent logs — and make it legible, testable, and something an analyst can act on.</sub>

#### Detection Engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** — Detection-as-code pipeline that compiles Sigma rules into Splunk SPL and Microsoft Sentinel KQL, fire-tested in CI, with MITRE ATT&CK + ATLAS coverage and a dedicated LLM/AI-app threat pack.
<br><sub>`Python` · `Sigma` · `Splunk SPL` · `Sentinel KQL` · `CI`</sub>

**[PromptHound](https://github.com/NotACop38/PromptHound)** — SIEM-ready detection library for attacks against LLM apps and AI agents. Sigma rules auto-convert to SPL + KQL, mapped to the OWASP LLM Top 10 and MITRE ATLAS, with a synthetic telemetry generator that exercises every rule offline.
<br><sub>`Python` · `OWASP LLM Top 10` · `MITRE ATLAS` · `detection-as-code`</sub>

**[SubStation](https://github.com/NotACop38/SubStation)** — Detection content for industrial-protocol attacks — Modbus, DNP3, Siemens S7 — mapped to MITRE ATT&CK for ICS. Bundled with a synthetic traffic simulator that emits benign and anomalous telemetry as PCAP and JSON, so OT detections validate with no PLC or live hardware.
<br><sub>`Python` · `Modbus / DNP3 / S7` · `ATT&CK for ICS` · `PCAP`</sub>

#### Digital Forensics & Incident Response

**[Casebound](https://github.com/NotACop38/Casebound)** — Local-first DFIR copilot that assembles a verified forensic timeline and an evidence-grounded narrative. Every AI claim has to cite a real event or it gets rejected — no hallucinated findings in the report.
<br><sub>`DFIR` · `local-first` · `timeline analysis` · `evidence-grounded AI`</sub>

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** — Self-hostable phishing-triage tool. Parse a suspicious `.eml`/`.msg`, defang IOCs, enrich via OSINT, and produce a transparent risk score with an analyst-ready report. Never sends, opens, or detonates — triage stays safe by construction.
<br><sub>`Python` · `email forensics` · `OSINT` · `IOC enrichment`</sub>

#### Reverse Engineering & Tooling

**[Sextant](https://github.com/NotACop38/Sextant)** — Reverse-engineers unknown binary formats and protocols through combined statistical and LLM structure inference, then tests every generated parser against your real sample captures.
<br><sub>`Rust` · `binary analysis` · `protocol RE` · `parser generation`</sub>

<p align="center"><img src="assets/divider.svg" width="100%" height="8" alt=""></p>

<p align="center">
  <sub><b>Languages</b>&nbsp;&nbsp;Python · Rust · C · Assembly (Intel x86)<br>
  <b>Tooling</b>&nbsp;&nbsp;Sigma · Splunk SPL · Sentinel KQL · MITRE ATT&CK / ATLAS · OWASP LLM Top 10</sub>
</p>

<p align="center">
  <sub>A habit, not a slogan: every project here ships with the thing that proves it works —<br>CI-tested rules, synthetic telemetry, real-sample validation, and evidence you can audit.</sub>
</p>
