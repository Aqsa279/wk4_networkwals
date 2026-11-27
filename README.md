# wk4_networkwals
# Week 4 â€“ Mediroza Website Security Assessment

**Trainee:** Aqsa Shafiq  
**Program:** Networkwalks Cybersecurity Internship (Batch B084)  
**Assessment period stated in the supplied report:** 24â€“29 November 2026  
**Target:** Mediroza General Hospital web application  
**Engagement:** Authorized assessment, as stated in the supplied Networkwalks report.

## Overview
This repository documents the Week 4 practical web-application security assessment. Work described in the supplied report covered authentication testing, protected-document access review, exposed-file/data-exposure review, directory discovery, risk assessment, and remediation planning.

## Scope and approach
The supplied report describes testing limited to the named target and states that social engineering, denial-of-service, and out-of-scope testing were prohibited. Activities were documented as:
- Reconnaissance and endpoint discovery
- Authentication and input-handling assessment
- Review of protected PDF access and password protection
- Review of exposed files and directory listings
- Evidence collection, risk rating, and remediation recommendations

## Key reported observations
| Area | Reported observation | Reported severity |
|---|---|---|
| Patient portal authentication | SQL injection was reported to permit authentication bypass | Critical |
| Directory/file exposure | Publicly discoverable paths and files were reported | Medium |
| Security headers | Missing or insufficient headers were noted | Low |
| Protected PDF documents | The report describes password-protected PDF access and password-recovery testing | Sensitive; details intentionally withheld |
| Server-side data exposure | The report describes exposure of confidential business information | High impact; details intentionally withheld |

Severity labels above reflect the supplied report and have not been independently revalidated in this repository.

## Tools mentioned in the report
- Kali Linux
- Nmap
- WhatWeb
- cURL
- FFUF
- Custom wordlist / SecLists
- Networkwalks password-cracker resource (referenced in the report)

## Repository layout
- `Recon/` â€“ sanitized reconnaissance notes
- `Evidence/` â€“ evidence register with sensitive values omitted
- `Screenshots/` â€“ safe, redacted screenshots may be added here
- `Reports/` â€“ sanitized assessment summary
- `Notes/` â€“ learning notes and methodology

## Responsible disclosure and privacy
The source report contains patient-identifying information, confidential medical-report screenshots, credentials/passwords, password hashes, and sensitive hospital/business data. **Those materials are deliberately not included in this public portfolio repository.** Do not upload the original PDF or unredacted screenshots. Replace screenshots only with properly redacted evidence that contains no patient data, credentials, tokens, hashes, or confidential records.

## Status
This repository is a sanitized portfolio summary based on the supplied Week 4 report. It is not a claim that every finding has been independently reproduced or remediated. Remediation status was not established by the supplied report.

