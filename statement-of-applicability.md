# Statement of Applicability (SoA)

## Overview

The **Statement of Applicability (SoA)** is one of the most important documents in an **ISO/IEC 27001 Information Security Management System (ISMS)**.

It defines which security controls from **Annex A** are applicable to the organization and explains how they are implemented.

The SoA is required by:

**ISO/IEC 27001 Clause 6.1.3 – Information Security Risk Treatment**

This document links the organization's **risk assessment results** with the **security controls implemented to mitigate those risks**.

In simple terms, the SoA answers three key questions:

* Which security controls apply to the organization?
* Why were those controls selected?
* How are those controls implemented?

---

# Purpose of the Statement of Applicability

The SoA provides transparency about how an organization manages security risks.

Its main purposes include:

* Documenting which controls are implemented
* Justifying why certain controls are excluded
* Demonstrating alignment between risks and security controls
* Providing evidence for auditors during certification audits

Because of this, the SoA becomes a **central reference document during ISO 27001 audits**.

---

# Annex A Controls

ISO 27001 provides a list of security controls in **Annex A**.

In the **2022 revision**, the number of controls was reduced from **114 to 93**.

These controls are grouped into four categories:

| Category                | Description                                                       |
| ----------------------- | ----------------------------------------------------------------- |
| Organizational Controls | Governance and security management policies                       |
| People Controls         | Security awareness and personnel responsibilities                 |
| Physical Controls       | Protection of facilities and physical assets                      |
| Technological Controls  | Technical security measures such as encryption and access control |

Organizations do **not need to implement every control**.

Instead, controls are selected based on the **risk assessment results**.

---

# Relationship Between Risk Assessment and SoA

The SoA is directly connected to the **risk treatment process**.

The process works as follows:

1. Conduct a risk assessment
2. Identify risks affecting assets
3. Decide how those risks should be treated
4. Select appropriate security controls
5. Document the selected controls in the SoA

Example:

| Risk                           | Selected Control                    |
| ------------------------------ | ----------------------------------- |
| Unauthorized access to systems | Access control policies             |
| Data leakage                   | Encryption and data loss prevention |

This ensures that security controls are implemented **based on actual risks**, rather than arbitrary decisions.

---

# Structure of a Statement of Applicability

Although ISO 27001 does not prescribe a strict format, most SoA documents contain several key fields.

Typical components include:

| Field                 | Description                                  |
| --------------------- | -------------------------------------------- |
| Control ID            | Reference number of the Annex A control      |
| Control Name          | Description of the control                   |
| Applicable            | Indicates whether the control is implemented |
| Justification         | Explanation for inclusion or exclusion       |
| Implementation Status | Implementation stage of the control          |

---

# Example SoA Entry

Example entry from a Statement of Applicability:

| Control ID | Control Name           | Applicable | Justification                                      | Implementation Status |
| ---------- | ---------------------- | ---------- | -------------------------------------------------- | --------------------- |
| A.6.7      | Remote Working         | Yes        | Employees access company systems remotely          | Implemented           |
| A.8.30     | Outsourced Development | No         | Organization does not perform software development | Not Applicable        |

This structure allows auditors to easily verify whether the organization has properly implemented its controls.

---

# Implementation Status

The SoA usually indicates the **implementation status** of each control.

Typical status options include:

| Status                | Meaning                                  |
| --------------------- | ---------------------------------------- |
| Implemented           | Control is fully operational             |
| Partially Implemented | Control exists but is not fully deployed |
| Planned               | Control implementation is scheduled      |
| Not Implemented       | Control has not yet been implemented     |

Auditors often review partially implemented controls to ensure that **implementation plans exist**.

---

# Why the SoA is Important for Audits

During ISO 27001 audits, the Statement of Applicability serves as a **roadmap for auditors**.

Auditors use it to:

* understand which controls should exist
* identify where to look for evidence
* verify control implementation

For example:

If the SoA indicates that **multi-factor authentication is implemented**, auditors will expect evidence such as:

* system configuration
* authentication policies
* access logs

Without a properly maintained SoA, the audit process becomes much more difficult.

---

# Common Mistakes in SoA Management

Organizations often make several mistakes when managing the Statement of Applicability.

---

## Missing Required Controls

Some organizations fail to include controls that are clearly necessary based on their risks.

This can lead to:

* audit findings
* security gaps
* nonconformities

---

## Poor Justification for Excluded Controls

When a control is excluded, the organization must provide a **clear explanation**.

Weak justifications such as:

"Not relevant"

are usually unacceptable during audits.

Instead, organizations should provide context.

Example:

"The organization does not perform software development activities, therefore controls related to secure development are not applicable."

---

## Lack of Regular Updates

The SoA must be updated whenever:

* new risks are identified
* controls are implemented or removed
* business processes change
* the ISMS scope is modified

Failing to update the SoA can result in **outdated documentation and audit issues**.

---

# Best Practices for Managing the SoA

Organizations should follow several best practices.

---

### Keep the SoA Linked to the Risk Register

Each control should correspond to a specific risk.

This ensures that controls are implemented for **clear risk treatment purposes**.

---

### Review the SoA Regularly

The SoA should be reviewed:

* during internal audits
* during management reviews
* when risk assessments are updated

---

### Maintain Clear Documentation

Evidence supporting control implementation should be easily accessible.

Examples include:

* policies
* procedures
* technical configurations
* training records

---

# Key Takeaways

The Statement of Applicability is a **core document within ISO 27001**.

Important points include:

* It connects **risk assessment results with security controls**
* It documents which **Annex A controls are implemented**
* It provides **justification for excluded controls**
* It acts as a **reference document during audits**

A well-maintained SoA demonstrates that an organization manages information security **in a structured and risk-driven manner**.
