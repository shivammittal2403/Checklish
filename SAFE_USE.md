# Safe and Authorized Use

## Required authorization

Before assessment activity begins, obtain written approval that identifies the legal entity, asset owners, in-scope assets and identities, dates, source addresses, physical locations, permitted methods, prohibited actions, maintenance windows, emergency contacts, data handling, evidence retention, and stop conditions.

## Prohibited activity in this framework

- Malware creation or modification.
- Credential theft, password/hash cracking, token capture, or use of exposed credentials.
- Persistence, destructive actions, extortion, data encryption, or denial of service.
- Exploit weaponization or instructions for bypassing security controls.
- Direct access to hidden services, illicit marketplaces, or stolen-data repositories.
- Lock manipulation, forced entry, unsafe radio disruption, or interference with OT/process safety.
- Collection of unrelated customer, employee, patient, payment, or personal data.

## Safe validation defaults

- Use test accounts, synthetic records, canary files, inert payload substitutes, and approved lab targets.
- Prefer configuration review, passive observation, owner-operated demonstrations, and logged control tests.
- Rate-limit automated checks and define abort thresholds for errors, latency, capacity, safety, or business impact.
- Do not cross a trust boundary until that path is explicitly authorized.
- Minimize screenshots and exports; mask secrets and unrelated personal or customer information.
- Remove temporary accounts, files, tokens, allow-list entries, captures, and configurations at closure.

## Special environments

For ATMs/payment terminals, OT/ICS/SCADA, telecom, medical/safety systems, physical sites, and production identity infrastructure, use a safety owner and change authority. Prefer passive or lab validation. Any action that could alter process state, availability, financial transactions, safety systems, or customer service requires scenario-specific written approval.

## Dark-web intelligence

Use lawful intelligence providers, approved feeds, counsel-directed processes, and internal incident-response channels. Do not publish or follow hidden-service addresses. Do not acquire contraband or stolen datasets. Corroborate claims without testing leaked credentials, and apply privacy, legal-hold, retention, and need-to-know controls.

## Evidence

Assign evidence IDs, record timestamps and asset identifiers, protect originals, hash files where appropriate, restrict access, and retain only what is necessary. Escalate urgent findings through the agreed notification path. Report limitations and inconclusive results plainly.
