# Security Policy

BIOSYNC processes attendance information and may integrate with biometric devices, local files, browser automation, and messaging services. Security and privacy reports are taken seriously.

## Supported versions

Security fixes are applied to the latest code on the `main` branch. Older snapshots and unofficial forks may not receive fixes.

## Reporting a vulnerability

Do not open a public issue for a vulnerability that could expose credentials, biometric identifiers, attendance records, phone numbers, institutional information, browser sessions, or remote access.

Report the issue privately to the repository owner using the contact method listed on the owner's GitHub profile. Include:

- A clear description of the vulnerability.
- The affected file, module, or workflow.
- Reproduction steps using synthetic data.
- The possible impact.
- A suggested mitigation, when available.

Do not include real student, employee, device, institution, or account data.

## Response process

The maintainer will aim to:

1. Acknowledge a valid report.
2. Reproduce and assess the issue.
3. Prepare a fix or mitigation.
4. Coordinate disclosure when appropriate.
5. Credit the reporter if they request recognition and responsible disclosure was followed.

No guaranteed response or resolution time is promised because BIOSYNC is currently maintained on a best-effort basis.

## Deployment guidance

Operators should:

- Keep credentials and secrets outside source control.
- Restrict biometric-device and administration networks.
- Use least-privilege accounts.
- Protect local attendance files and backups.
- Restrict access to WhatsApp browser profiles and session data.
- Review logs before sharing them.
- Rotate credentials immediately after suspected exposure.
- Use synthetic data for development and demonstrations.
