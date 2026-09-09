# Incident Response Report

## 1. Incident Overview

**Project:** Security Alert Monitoring & Incident Response
**Platform:** Splunk SIEM
**Environment:** Controlled / simulated security monitoring environment

This project demonstrates a basic Security Operations Center (SOC) workflow using Splunk to ingest, search, analyze, and prioritize security events.

---

## 2. Detection

Security events were analyzed in Splunk to identify potentially suspicious activity, including:

* Failed authentication attempts
* Malware-related alerts
* Suspicious IP activity
* Unusual access behavior
* File access events

---

## 3. Alert Analysis

The collected events were reviewed to determine:

* Event type
* Source information
* User involved
* Frequency of activity
* Potential security impact
* Alert severity

---

## 4. Severity Classification

### Critical

Events indicating potentially severe impact, such as ransomware-related activity or malware combined with suspicious file access.

### High

Significant malware-related events requiring investigation.

### Medium

Repeated authentication failures or other suspicious activity requiring further analysis.

### Low

Normal or expected activity with no clear indication of compromise.

---

## 5. Investigation

The investigation involved reviewing security logs and correlating related events.

The analysis focused on:

* Identifying suspicious users
* Identifying suspicious IP addresses
* Reviewing authentication activity
* Investigating malware alerts
* Examining related file access events

---

## 6. Recommended Response

For a real-world incident, appropriate response actions could include:

1. Isolate affected systems.
2. Disable or secure compromised accounts.
3. Block confirmed malicious network indicators.
4. Perform endpoint and antivirus scans.
5. Review related authentication and file-access activity.
6. Preserve relevant logs for further investigation.

These actions are documented as simulated incident-response recommendations for this educational project.

---

## 7. Incident Status

**Status:** Investigated / Simulated

The project demonstrates the investigation and documentation workflow rather than performing response actions against real production systems.

---

## 8. Key Learning Outcomes

Through this project, I practiced:

* SIEM-based log analysis
* Security alert monitoring
* Authentication anomaly detection
* Malware alert investigation
* Suspicious IP identification
* Alert severity classification
* Incident-response documentation
* SOC investigation workflow
