# Authorized Security Assessment Framework

Version: 2026.09  
Baseline date: 10 September 2026

This project is a defensive checklist framework for authorized security assessments. It retains the original Excel workbook filenames and worksheet names, extends each workbook with current control-validation items, and adds a normalized master workbook covering 39 domains and 704 assessment rows.

## Start here

1. Read `SAFE_USE.md` and approve written rules of engagement.
2. Open `Security_Assessment_Framework_2026-09.xlsx`.
3. Use the `Index` sheet to select a domain and filter `Master Checklist` by domain, category, priority, status, or owner.
4. Use `updated_checklists/` when an engagement needs the familiar legacy workbook layout.
5. Record reproducible evidence, protect sensitive material, track remediation, and retest fixes.

## Included

- `Security_Assessment_Framework_2026-09.xlsx`: normalized master checklist, domain index, standards register, and safety guidance.
- `updated_checklists/`: all 17 original Excel workbooks with their filenames, worksheet names, and column layouts retained. New September 2026 defensive checks were added, and operationally unsafe content was removed or replaced.
- `INDEX.md`: domain-to-file navigation and coverage map.
- `STANDARDS.md`: authoritative references and version notes current to the baseline date.
- `CHANGELOG.md`: summary of changes and safety cleanup.
- `SAFE_USE.md`: authorization, safety, privacy, and evidence-handling guardrails.
- `SOURCE_MANIFEST.md`: inventory and disposition of the supplied archive.

## Coverage

The master workbook covers penetration testing, red team, dark-web intelligence, malware analysis, AI/LLM systems, ATM/payment terminals, network, firewall, vendor/third-party risk, thick clients, SCADA/ICS/OT, web, API, Android, iOS, Wi-Fi, cloud, containers/Kubernetes, identity/AD/Entra, email, collaboration platforms, phishing resilience, source code, CI/CD, software supply chain, hardware/firmware/IoT, telecom, databases, virtualization, endpoint, browser extensions, secrets, cryptography/TLS, logging/SIEM/SOC, data/privacy, ransomware readiness, physical security, vulnerability management, and reporting/evidence.

## Safety boundary

This material does not provide malware creation, credential theft or recovery, persistence, exploit weaponization, denial-of-service, physical bypass, or dark-web access instructions. Use test identities, synthetic data, approved lab environments, rate limits, and owner-observed evidence. Stop when a test could affect safety, availability, unrelated data, or out-of-scope systems.

## Tailoring

Not every row applies to every engagement. Mark non-applicable rows with a documented reason. Replace generic evidence expectations with system-specific artifacts and map local regulations, contractual obligations, safety requirements, and vendor baselines before use.

## Version caution

Standards evolve. The versions in this package were checked against authoritative sources on 10 September 2026. Reconfirm versions, errata, implementation guidance, and legal obligations before each engagement. Drafts and in-progress revisions are identified as informative rather than final requirements.
