# Incident Response Plan

A formal incident response plan for a ransomware or unauthorized network intrusion
in a healthcare environment, structured on the NIST 800-61 lifecycle.

---

## 1. Incident Overview

**Incident type:** Ransomware or unauthorized network intrusion originating from an endpoint device.

**Severity:** CRITICAL

**Justification:** The organization stores sensitive medical insurance records. Immediate
isolation is required to prevent further data loss and to meet HIPAA requirements for
safeguarding protected health information.

---

## 2. Detection & Analysis

**Identify**
- Document all visual evidence of the compromise on the affected employee's screen.
- Capture timestamps, error messages, and any ransom notes or unexpected system behavior.

**Assess**
- Evaluate the scope of the intrusion.
- Determine whether other connected systems show similar indicators of compromise.

---

## 3. Containment

**Immediate isolation**
- Disconnect the affected device from the network by unplugging the ethernet cable.
- Disable wireless connectivity on the device.
- Goal: stop lateral movement and prevent data exfiltration.

---

## 4. Eradication

**Scan for vulnerabilities**
- Run deep scans to identify the specific malware strain.
- Trace the strain back to the vulnerability that allowed the breach.

**Remove the threat**
- Erase the malware from affected systems.
- Patch the identified vulnerability and close any related security gaps.
- Confirm the threat is fully removed before recovery begins.

---

## 5. Recovery

**System rebuilding**
- Rebuild affected systems from a trusted, clean disk image.

**Data restoration**
- Restore data only from secure, verified-uncompromised backups.

**Enhanced monitoring**
- Deploy continuous monitoring on restored devices before returning them to normal operations.

---

## 6. Roles & Responsibilities

**Security Analyst**
- First responder. Confirms the threat and immediately isolates the affected device from the network.
- Documents the incident and produces the incident write-up.

**IT & Security Staff**
- Performs technical analysis and runs vulnerability scans.
- Eradicates the malware, patches affected systems, and restores data to a clean state.

**Legal & Compliance**
- Reviews the breach against applicable data protection law, including HIPAA.
- Manages regulatory reporting timelines for the incident.

**Public Relations**
- Coordinates timely notification to affected customers regarding the status of their personal data.
