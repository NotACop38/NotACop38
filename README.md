<h1 align="center">Tyler Graves</h1>

<p align="center">
  <em>Detection engineering &middot; digital forensics &amp; incident response &middot; security tooling</em>
</p>

<p align="center">
  Boise, Idaho
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/tyler-graves-security">LinkedIn</a>
  &nbsp;&middot;&nbsp;
  <a href="mailto:tgraves38@protonmail.com">Email</a>
</p>

<p align="center">
  <img alt="GIAC GFACT" src="https://img.shields.io/badge/GIAC-GFACT-8A1538?style=flat-square&labelColor=2B2B2B">
  <img alt="GIAC GSEC" src="https://img.shields.io/badge/GIAC-GSEC-8A1538?style=flat-square&labelColor=2B2B2B">
  <img alt="GIAC GCIH" src="https://img.shields.io/badge/GIAC-GCIH-8A1538?style=flat-square&labelColor=2B2B2B">
  <img alt="GIAC Advisory Board" src="https://img.shields.io/badge/GIAC-Advisory%20Board-334155?style=flat-square&labelColor=2B2B2B">
</p>

---

### Selected Work

<sub>Six tools spanning the defensive lifecycle — author detections, prove them out offline, and run the investigation when one fires.</sub>

#### Detection Engineering

**[Sigma-Forge](https://github.com/NotACop38/Sigma-Forge)** — Detection-as-code pipeline that compiles Sigma rules into Splunk SPL and Microsoft Sentinel KQL, fire-tested in CI with MITRE ATT&CK + ATLAS coverage and a dedicated LLM/AI-app threat pack.
<br><sub>`Python` · `Sigma` · `Splunk SPL` · `Sentinel KQL` · `CI`</sub>

**[PromptHound](https://github.com/NotACop38/PromptHound)** — SIEM-ready detection library for attacks against LLM apps and AI agents. Sigma rules auto-convert to SPL + KQL, mapped to the OWASP LLM Top 10 and MITRE ATLAS, with a synthetic telemetry generator that validates every rule offline.
<br><sub>`Python` · `OWASP LLM Top 10` · `MITRE ATLAS` · `detection-as-code`</sub>

**[SubStation](https://github.com/NotACop38/SubStation)** — Detection content for industrial protocol attacks — Modbus, DNP3, Siemens S7 — mapped to MITRE ATT&CK for ICS. Ships with a synthetic traffic simulator that emits benign and anomalous telemetry as PCAP and JSON, so OT detections validate with no PLC or live hardware.
<br><sub>`Python` · `Modbus / DNP3 / S7` · `ATT&CK for ICS` · `PCAP`</sub>

#### Digital Forensics & Incident Response

**[Casebound](https://github.com/NotACop38/Casebound)** — Local-first DFIR copilot that assembles a verified forensic timeline and an evidence-grounded narrative. Every AI claim must cite a real event or be rejected — no hallucinated findings in the report.
<br><sub>`DFIR` · `local-first` · `timeline analysis` · `evidence-grounded AI`</sub>

**[PhishBowl](https://github.com/NotACop38/PhishBowl)** — Self-hostable phishing-triage tool. Parse a suspicious `.eml`/`.msg`, defang IOCs, enrich via OSINT, and produce a transparent risk score with an analyst-ready report. Analysis-only by design — never sends, opens, or detonates.
<br><sub>`Python` · `email forensics` · `OSINT` · `IOC enrichment`</sub>

#### Reverse Engineering & Tooling

**[Sextant](https://github.com/NotACop38/Sextant)** — Reverse-engineers unknown binary formats and protocols through combined statistical and LLM structure inference, with every generated parser tested against your real sample captures.
<br><sub>`Rust` · `binary analysis` · `protocol RE` · `parser generation`</sub>

---

<p align="center">
  <sub>Defensive security only — all tooling is built for analysis, detection, and response.</sub>
</p>
