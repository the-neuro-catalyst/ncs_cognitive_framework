# Security Policy

## Supported Versions

| Branch / Tag | Supported |
|---|---|
| `main` | ✅ Active |
| Release tags (`v*`) | ✅ Latest only |
| Older tags | ❌ No backport |

## Scope

In scope:
- Memory persistence layer (Sled-backed)
- Governance and veto mechanisms
- Configuration loading and secret handling
- Ingestion and reader pipeline

Out of scope:
- Third-party dependencies (report upstream)
- Infrastructure or hosting outside this repository
- Informational findings with no exploitable path

## Reporting a Vulnerability

Do not open public issues for security vulnerabilities.

Use GitHub Security Advisories:
- <https://github.com/the-neuro-catalyst/ncc-zer0/security/advisories/new>

Include in your report:
- Affected component and file path
- Reproduction steps (minimal reproducible case preferred)
- Impact assessment (confidentiality, integrity, availability)
- Suggested mitigation if available

## Response Timeline

| Stage | Target |
|---|---|
| Acknowledgement | Within 72 hours |
| Triage and severity assessment | Within 7 days |
| Fix or mitigation | Dependent on severity |
| Public disclosure | Coordinated with reporter |

Critical severity findings will be prioritized immediately.

## Disclosure Policy

This project follows coordinated disclosure. We ask that reporters:
- Allow reasonable time for triage and remediation before public disclosure
- Avoid exploiting vulnerabilities beyond what is necessary to demonstrate impact
- Treat discovered information as confidential until a fix is available

We commit to:
- Acknowledging receipt promptly
- Keeping reporters informed of progress
- Crediting reporters in release notes unless anonymity is requested

## Severity Guidance

| Severity | Examples |
|---|---|
| Critical | RCE, auth bypass, memory exfiltration |
| High | Privilege escalation, governance bypass, data corruption |
| Medium | Information disclosure, config injection |
| Low | Minor logic errors with limited impact |

## License

This project is released under [UNLICENSE](LICENSE). Security obligations described here are voluntary commitments, not contractual guarantees.
