# Ember Vault: Executive Report Rubric

## Scenario-specific required conclusions

This is a dual-actor scenario. The primary espionage actor targets `j.patel` with the delivered M&A lure, compromises `FIN-WS22`, establishes endpoint persistence, and accesses deal-room material. Endpoint Sysmon, proxy/DNS, and the valid lure-browsing/malware PCAPs are the authoritative path; the Slack `offer_talk.png` supports the manufactured insider narrative but does not prove `j.patel` voluntarily disclosed data.

The actor pivots into engineering/CI through `build-agent-03`, GitHub audit activity, and the modified release workflow. CI/cloud evidence must distinguish repository modification, credential availability, AWS use, and Kubernetes actions. The cloud and network records support staging and outbound transfer of the M&A collection. The real and decoy VPN sessions must be separated by device, source, and follow-on activity rather than treated equally.

A second actor performs selective ransomware activity against the named VDI/file-server targets as cover. The ransom notes and encryption effects are real, but they do not explain the earlier M&A access and CI/cloud chain. Report the ransomware and espionage tracks separately unless a shared observable is independently demonstrated.

The intentionally malformed SIEM export is a collection limitation and should be repaired analytically from source logs, not treated as attacker anti-forensics. Containment includes affected user sessions/endpoints, GitHub/CI credentials and workflow rollback, AWS/Kubernetes role and secret rotation, exfiltration scoping, ransomware isolation/recovery, and rejection of the unsupported insider accusation.

## Scoring

- 30% accurate, normalized timeline with artifact citations
- 25% complete entry, pivot, persistence, privilege, and impact analysis
- 20% correct clustering of related, unrelated, benign, and false-signal activity
- 15% disciplined confidence labels and treatment of telemetry gaps
- 10% executive-quality remediation, ownership, and sequencing

## Automatic deductions

- Unsupported attribution or invented observables
- Collapsing every suspicious event into a single incident
- Treating attempted access as successful access
- Treating access as exfiltration without transfer or receipt evidence
- Treating missing logs as proof that activity did not occur
- Omitting material contradictory or benign evidence

Every high-impact conclusion should cite two independent artifacts where available and preserve exact identities, hosts, IP addresses, object names, and timestamps.
