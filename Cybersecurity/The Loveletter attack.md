**ID:** 202609030036
**Tags:** #attack-vector #social-engineering #malware
**Related Notes:** [[Social engineering]], [[Phishing]], [[Examples of malware attacks]], [[Malware]]

---

## Threat Description
Occurring in 2000, "LOVE-LETTER-FOR-YOU" (ILOVEYOU) was a destructive worm-like attack that combined social engineering techniques with script automation to harvest credentials and overwrite victim files.

## Execution Path & Attack Mechanics
1. **Initial Access:** Sent via an email with the subject line "ILOVEYOU" and a malicious attachment titled `LOVE-LETTER-FOR-YOU.TXT.vbs`.
2. **Exploitation:** Exploited human curiosity ([[Social engineering]]) to trick users into executing the VBScript file.
3. **Impact:** Scanned the local Windows address book and automatically e-mailed copies of itself to all contacts while overwriting image and media files on local storage.

## Prevention & Remediation
* **Remediation:** Email attachment filtering, disabling automatic execution of VBScripts, user awareness training regarding suspicious file extensions.

## References
* Source: Google Cybersecurity Course - History of Cybersecurity