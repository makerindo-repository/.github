# Security Policy // PT Makerindo Prima Solusi

**PT Makerindo Prima Solusi** commits to maintaining the highest security, integrity, and confidentiality standards across all our hardware, firmware, and software platforms in compliance with **ISO/IEC 27001:2022**.

---

## 1. Scope & Supported Platforms

We actively support and remediate security vulnerabilities across all production releases and active repositories under the `@makerindo-repository` organization.

| Asset Type | Supported Architecture | Status |
|---|---|---|
| **Industrial IoT Firmware** | ESP32 (ESP-IDF), STM32, LoRaWAN Telemetry | Supported |
| **Enterprise Cloud & Backend** | Go (Gin, GORM), Python (FastAPI), Node.js | Supported |
| **Enterprise Web Portals** | Next.js (App Router), React, TypeScript | Supported |
| **Mobile Applications** | Flutter (Clean Architecture, BLoC Pattern) | Supported |

---

## 2. Reporting a Vulnerability

If you identify a vulnerability, potential data exposure, credential leak, or architectural flaw in any Makerindo service:

1. **Do NOT open a public GitHub issue** or share details publicly.
2. Email your detailed report immediately to:
   - **Official Security Contact**: `makerdotindo@gmail.com`
3. Include in your report:
   - Target repository, URL, or hardware firmware version.
   - Step-by-step reproduction instructions or Proof-of-Concept (PoC).
   - Potential impact and severity assessment adhering to CVSS v3.1.

---

## 3. SLA & Response Timeline

Our security engineering team adheres to the following response timeline:

- **Initial Acknowledgment**: Within 24 hours of receipt.
- **Triage & Risk Validation**: Within 3 business days.
- **Remediation & Patch Deployment**: Within 7 to 14 business days depending on severity.

We appreciate responsible security disclosures and protect reporters under our Safe Harbor principles.
