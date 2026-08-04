# Ember Vault: Executive Report Rubric

## Scenario-specific required conclusions

Use the Windows event corpus to establish the first malicious execution, persistence, credential access, and follow-on network activity. Repeated benign service/task events are noise; require a consistent user/host/timestamp and corroborating file or network evidence. The final answer must separate confirmed actions from plausible but unobserved steps and state any missing telemetry.

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
