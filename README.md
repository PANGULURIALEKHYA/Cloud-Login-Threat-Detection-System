# Cloud Login Threat Detection System

| **Title** | Cloud Login Threat Detection System |
|------------|-------------------------------------|
| **Description** | Microsoft Azure cloud security project demonstrating cloud login threat detection using Microsoft Sentinel, Microsoft Defender, Microsoft Entra ID, Log Analytics Workspace, and Kusto Query Language (KQL). |
| **Author** | Alekhya Panguluri |

---

# Introduction

This project demonstrates how Microsoft Azure security services can be used to detect, investigate, and analyse suspicious cloud login activity. The project focuses on monitoring Microsoft Entra ID sign-in logs, identifying repeated failed login attempts using KQL, generating incidents through Microsoft Sentinel analytics rules, and investigating alerts in Microsoft Defender.

---

# Project Objectives

- Deploy a cloud security monitoring environment in Microsoft Azure.
- Configure Microsoft Sentinel with a Log Analytics Workspace.
- Monitor Microsoft Entra ID sign-in activity.
- Develop KQL queries to detect suspicious login behaviour.
- Create analytics rules for automated alert generation.
- Investigate incidents using Microsoft Defender.
- Document the complete detection and investigation process.

---

# Technologies Used

- Microsoft Azure
- Microsoft Sentinel
- Microsoft Defender
- Microsoft Entra ID
- Log Analytics Workspace
- Azure Resource Manager
- Kusto Query Language (KQL)

---

# Project Workflow

1. Create Azure Resource Group.
2. Configure Log Analytics Workspace.
3. Deploy Microsoft Sentinel.
4. Collect Microsoft Entra ID sign-in logs.
5. Develop KQL detection queries.
6. Create Sentinel Analytics Rules.
7. Generate security incidents.
8. Investigate alerts in Microsoft Defender.
9. Analyse findings and document the investigation.

---

# Skills Demonstrated

- Cloud Security Monitoring
- Security Operations (SOC)
- Microsoft Sentinel
- Microsoft Defender
- Microsoft Entra ID
- Azure Administration
- Kusto Query Language (KQL)
- Log Analysis
- Security Incident Investigation
- Threat Detection
- Incident Documentation

---

# Repository Structure

```
Cloud-Login-Threat-Detection-System/
│
├── README.md
├── docs/
│   ├── Cloud_Login_Threat_Detection_SOC_Incident_Report.pdf
│   └── README.md
│
└── screenshots/
    ├── 01-Resource-Manager.png
    ├── 02-Log-Analytics-Workspace-Overview.png
    ├── ...
    └── README.md
```

---

# Key Outcomes

- Successfully configured Microsoft Sentinel for cloud security monitoring.
- Collected Microsoft Entra ID sign-in logs.
- Developed KQL queries to identify suspicious login activity.
- Created automated analytics rules for incident generation.
- Investigated incidents using Microsoft Defender.
- Produced a detailed SOC incident report documenting the investigation.

---

# Documentation

The complete technical report is available in the **docs** folder.

---

# Screenshots

The **screenshots** folder contains visual evidence of the Azure deployment, KQL queries, Microsoft Sentinel analytics rules, incident generation, and Microsoft Defender investigation process.

---

# Future Enhancements

- Detect impossible travel login events.
- Monitor risky user sign-ins.
- Implement automated incident response using Logic Apps.
- Expand detection rules for additional cloud threats.
