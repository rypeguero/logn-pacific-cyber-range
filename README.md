<div align="center">

# Log(N) Pacific SOC Cyber Range

### Hands-on SOC investigations, threat hunting and incident reporting with Microsoft security tools

![Microsoft Sentinel](https://img.shields.io/badge/Microsoft-Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Defender](https://img.shields.io/badge/Microsoft-Defender-00A4EF?style=for-the-badge&logo=microsoft&logoColor=white)
![KQL](https://img.shields.io/badge/Language-KQL-5C2D91?style=for-the-badge)
![MITRE ATT&CK](https://img.shields.io/badge/Framework-MITRE%20ATT%26CK-C62828?style=for-the-badge)

</div>

---

## Overview

This repository documents hands-on Security Operations Center work performed in a controlled cyber range. The investigations demonstrate alert triage, endpoint analysis, KQL threat hunting, timeline reconstruction, MITRE ATT&CK mapping and remediation planning.

## Featured Investigations

| Investigation | Summary | Tools |
|---|---|---|
| [Hide Your RDP: Password Spray Leads to Full Compromise](./threat-hunting/hide-your-rdp-password-spray-to-full-compromise.md) | Traces an RDP password-spray compromise through execution, persistence, defense evasion, discovery, command-and-control and attempted exfiltration. | Sentinel, Defender for Endpoint, KQL |
| [Nimbus Health: Valid-Account Compromise](./threat-hunting/Nimbus%20Health%20Threat%20Hunt%20Report.md) | Reconstructs external access, lateral movement and sensitive-data collection performed through a compromised billing account. | Sentinel, Defender for Endpoint, KQL |

## Skills Demonstrated

- Alert triage and evidence validation
- Microsoft Sentinel and Defender for Endpoint investigations
- KQL-based log analysis and threat hunting
- Authentication, process, file and network telemetry analysis
- Incident timeline reconstruction
- MITRE ATT&CK technique mapping
- Severity assessment, containment and remediation recommendations
- Clear analyst-style reporting

## Technology Stack

`Microsoft Sentinel` · `Microsoft Defender for Endpoint` · `KQL` · `Azure` · `Tenable.io` · `MITRE ATT&CK` · `NIST`

## Investigation Workflow

```text
Alert or hypothesis → Scope the activity → Query telemetry → Build the timeline → Map techniques → Assess impact → Recommend remediation
```

## Environment Note

All work in this repository comes from authorized, controlled cyber range scenarios. No private, sensitive or unauthorized production data is included.

---

<div align="center">

**Ryan A. Peguero · Security Operations · Threat Hunting**

</div>
