# Chris Reddy

**Security Operations → Cloud Security Engineer.** AWS-focused, currently 
studying for Solutions Architect – Associate with Security Specialty next.

Below is hands-on work in detection engineering, threat hunting, and 
vulnerability management. My cloud security build-out starts alongside 
the SAA cert — first project is a Terraform-deployed AWS security baseline.

**Certifications:** AWS Certified Cloud Practitioner

[LinkedIn](https://linkedin.com/in/chrismreddy) · [X](https://x.com/chrisisntreddy)

---

## 🚨 Security Operations & Detection

| Project | What it does | Stack |
|---|---|---|
| **[SOC + Honeynet in Azure](https://github.com/chrisreddy1/Azure-SOC)** | Live honeynet ingesting Windows, Linux, and network telemetry into Microsoft Sentinel. Hardening with NSG restrictions and private endpoints cut security incidents from 270 to 0 across matched 24-hour windows. | Azure, Sentinel, Log Analytics, KQL, NSGs, Private Endpoints |
| **[Threat Hunt: Insider Data Exfiltration](https://github.com/chrisreddy1/threat-hunting-scenario-insider-threat)** | Endpoint hunt for unauthorized archiving and staged exfiltration, with the KQL queries and a written incident timeline. | Defender for Endpoint, KQL, MITRE ATT&CK |
| **[Threat Hunt: Tor Browser Usage](https://github.com/chrisreddy1/threat-hunting-scenario-tor)** | Detected unsanctioned Tor installation and traffic through process, file, and network telemetry. Produced hunt queries and policy recommendations. | Defender for Endpoint, KQL, MITRE ATT&CK |

## 🛡️ Vulnerability Management & Governance

| Project | What it does | Stack |
|---|---|---|
| **[Vulnerability Management Program](https://github.com/chrisreddy1/vulnerability-management-program)** | Built a full scan-remediate-verify lifecycle: authenticated scanning, risk-ranked findings, scripted remediation, and rescan validation. | Tenable, PowerShell, Windows Server, CVSS |
| **[NIST Security Assessment](https://github.com/chrisreddy1/NIST-Assessment)** | Control gap assessment against NIST 800-53, mapping findings to control families with prioritized remediation guidance. | NIST 800-53, risk assessment, control mapping |

---

## Tooling

**Cloud** Azure (Sentinel, Defender for Endpoint, Log Analytics, NSGs, 
Key Vault) · AWS (IAM, S3, EC2, VPC, CloudTrail)

**Detection & Analysis** KQL · MITRE ATT&CK · Wireshark · PowerShell

**Vulnerability & Governance** Tenable · NIST 800-53 · CVSS
