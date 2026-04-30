# Caybara-Incident-Response-Plan
Comprehensive Incident Response Plan for Capybara Unlimited covering the full NIST IR lifecycle. Includes defined roles, severity-based detection, containment procedures, KPIs, a structured communication plan, and tailored playbooks for malware, phishing, and denial-of-service incidents.
# Incident Response Plan — Capybara Unlimited

**Analyst:** Samuel Weiss
**Organization:** Capybara Unlimited (Medium-Sized Organization)
**Framework:** NIST Cybersecurity Framework — Incident Response Process

---

## Overview

This project delivers a comprehensive **Incident Response Plan (IRP)** for Capybara Unlimited, a medium-sized organization. The plan provides structured procedures for detecting, responding to, and recovering from cybersecurity incidents, including role definitions, lifecycle guidance, KPIs, playbooks, and communication protocols.

---

## Files

| File | Description |
|------|-------------|
| `_INCIDENT_RESPONSE__Incident_Response_Plan__Capybara_Unlimited___Samuel_Weiss_.docx` | Full Incident Response Plan including lifecycle, roles, KPIs, communication plan, playbooks, and maintenance schedule |

---

## Scope

Covers all IT systems, networks, applications, and personnel including internal staff, third-party vendors, and cloud-based services. Applies to the following incident types:

- Malware infections
- Phishing attacks
- Insider threats
- Denial-of-Service (DoS/DDoS) attacks
- Data breaches

---

## Plan Structure

### I. Objectives
Minimize impact, restore operations, enhance security posture, and meet regulatory requirements.

### II. Scope
All in-scope assets including corporate-managed and approved third-party systems handling organizational data.

### III. Roles & Responsibilities

| Role | Responsibility |
|------|---------------|
| Incident Command | Single decision authority; prioritization and escalation |
| SOC Analysts | Continuous monitoring, triage, and incident validation |
| Forensic Specialists | Evidence preservation, chain of custody, root cause analysis |
| IT Administrators | Containment, eradication, and recovery execution |
| Legal & Compliance | Regulatory reporting and breach notification |
| Sales & Marketing | Internal and external communications management |
| All Employees | Incident reporting and adherence to IR directives |

### IV. Incident Response Lifecycle (NIST)
1. **Preparation** — Policies, training, tools, playbooks
2. **Detection & Analysis** — SIEM, EDR, network log monitoring; severity classification
3. **Containment** — Immediate, short-term, and long-term containment actions
4. **Eradication** — Malware removal and root cause remediation
5. **Recovery** — System restoration from backup and post-incident monitoring
6. **Post-Incident Analysis** — Timeline creation, documentation, and process improvement

### V. Communication Plan
- Internal: Need-to-know escalation with time-stamped audit trail
- External: Legally validated disclosures coordinated with Incident Command

### VI. Key Performance Indicators (KPIs)

| KPI | Description |
|-----|-------------|
| Time to Detect (TTD) | Elapsed time from incident occurrence to detection |
| Time to Contain (TTC) | Time to isolate affected systems after detection |
| Time to Recover Baseline Security Posture (TTRBSP) | Time to restore systems to approved baseline |
| Incident Closure Rate | Percentage of incidents closed within defined timeframes |
| Post-Incident Improvement Rate | Percentage of corrective actions implemented |

### VII. Common Mistakes & Mitigations
- Overlooking early indicators
- Inadequate documentation
- Premature recovery before full eradication
- Neglecting post-incident reviews

### VIII. Tools & Techniques

| Phase | Tools |
|-------|-------|
| Detection | Splunk, QRadar, Snort, Suricata, CrowdStrike, SentinelOne |
| Containment | Cisco ISE, Palo Alto, Fortinet |
| Eradication | Sophos, Malwarebytes, Windows Defender |
| Recovery | Veeam, Acronis |
| Analysis | FTK, EnCase, Wireshark |

---

## Appendix — Playbooks

### Malware Infection Playbook
Covers identification, static analysis, dynamic sandbox analysis, network traffic analysis, persistence mechanism investigation, eradication, and post-incident reporting.

### Phishing Playbook
Covers email header analysis, quarantine procedures, user interaction verification, account remediation, employee notification, and reoccurrence monitoring.

### Denial-of-Service Playbook
Covers traffic characterization, volume assessment, source identification, affected service mapping, firewall rule implementation, and mitigation effectiveness monitoring.

---

## Review & Maintenance

- **Annual Review:** IRP reviewed and updated at least once per year
- **Ongoing Training:** Regular tabletop and simulation exercises with documented outcomes
- **Internal Audits:** Periodic first-party audits with tracked findings and remediation

---

## GitHub Description

> Comprehensive Incident Response Plan for Capybara Unlimited covering the full NIST IR lifecycle. Includes defined roles, severity-based detection, containment procedures, KPIs, a structured communication plan, and tailored playbooks for malware, phishing, and denial-of-service incidents.
