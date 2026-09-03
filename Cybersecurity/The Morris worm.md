**ID:** 202609030037
**Tags:** #attack-vector #history #malware #worm
**Related Notes:** [[Malware]], [[Examples of malware attacks]], [[Communication and network security]]

---

## Threat Description
Released in November 1988, the Morris Worm was one of the earliest computer worms distributed across the internet, designed originally to measure the size of the web.

## Execution Path & Attack Mechanics
1. **Initial Access:** Self-propagated across Unix systems by exploiting known vulnerabilities in `sendmail`, `finger`, and weak passwords via dictionary attacks.
2. **Exploitation Defect:** The code lacked logic to check if a system was already infected, repeatedly re-infecting target hosts.
3. **Impact:** Massive Denial of Service (DoS) conditions as infected machines ran out of memory and crashed, rendering large portions of the early internet unusable.

## Prevention & Remediation
* **Historical Impact:** Led directly to the creation of the first Computer Emergency Response Team (CERT) to coordinate response efforts during cyber incidents.

## References
* Source: Google Cybersecurity Course - History of Cybersecurity