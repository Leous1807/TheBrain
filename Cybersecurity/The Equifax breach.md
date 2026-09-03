**ID:** 202609030035
**Tags:** #attack-vector #incident #data-breach
**Related Notes:** [[SPII]], [[PII]], [[Examples of malware attacks]], [[Security assessment and testing]]

---

## Threat Description
In 2017, credit reporting agency Equifax suffered one of the largest data breaches in history, leading to the unauthorized exposure of sensitive data belonging to over 143 million consumers.

## Execution Path & Attack Mechanics
1. **Initial Access:** Exploited an unpatched Apache Struts vulnerability in an external web application.
2. **Exploitation & Pivot:** Malicious actors gained access, moved laterally across internal networks, and extracted data undetected for months due to expired security certificates.
3. **Impact:** Massive exposure of [[SPII]] (names, Social Security numbers, birth dates, driver's license numbers), resulting in over $500 million in federal settlements and legal penalties.

## Prevention & Remediation
* **Remediation:** Strict patch management schedules, continuous vulnerability scanning, certificate management, and network segmentation.

## References
* Source: Google Cybersecurity Course - History of Cybersecurity