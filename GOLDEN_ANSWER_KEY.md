# Operation Ember Vault — Golden Answer Key

This is a dual-actor scenario. The primary espionage actor targets `j.patel` with the delivered M&A lure, compromises `FIN-WS22`, establishes endpoint persistence, and accesses deal-room material. Endpoint Sysmon, proxy/DNS, and the valid lure-browsing/malware PCAPs are the authoritative path; the Slack `offer_talk.png` supports the manufactured insider narrative but does not prove `j.patel` voluntarily disclosed data.

The actor pivots into engineering/CI through `build-agent-03`, GitHub audit activity, and the modified release workflow. CI/cloud evidence must distinguish repository modification, credential availability, AWS use, and Kubernetes actions. The cloud and network records support staging and outbound transfer of the M&A collection. The real and decoy VPN sessions must be separated by device, source, and follow-on activity rather than treated equally.

A second actor performs selective ransomware activity against the named VDI/file-server targets as cover. The ransom notes and encryption effects are real, but they do not explain the earlier M&A access and CI/cloud chain. Report the ransomware and espionage tracks separately unless a shared observable is independently demonstrated.

The intentionally malformed SIEM export is a collection limitation and should be repaired analytically from source logs, not treated as attacker anti-forensics. Containment includes affected user sessions/endpoints, GitHub/CI credentials and workflow rollback, AWS/Kubernetes role and secret rotation, exfiltration scoping, ransomware isolation/recovery, and rejection of the unsupported insider accusation.
