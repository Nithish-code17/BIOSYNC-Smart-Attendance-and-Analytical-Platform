# Contributing to BIOSYNC

Thank you for helping improve BIOSYNC. Contributions that make the project safer, easier to install, more reliable, or better documented are welcome.

## Before you begin

- Read the README and existing issues.
- Do not commit biometric records, student data, phone numbers, credentials, browser profiles, API keys, or institutional files.
- Use anonymized or synthetic data in tests and examples.
- Keep changes focused so they can be reviewed safely.

## Ways to contribute

- Report reproducible bugs.
- Improve installation and deployment documentation.
- Add tests for attendance processing and report generation.
- Improve error handling, logging, recovery, and device monitoring.
- Add support for additional input formats or biometric-device integrations.
- Improve accessibility and usability of generated reports.

## Development setup

1. Fork the repository and create a branch from `main`.
2. Create and activate a Python virtual environment.
3. Install the dependencies documented in the README or requirements file.
4. Configure local paths and credentials through environment variables or ignored configuration files.
5. Test with synthetic data only.

Example branch names:

```text
fix/duplicate-punch-handling
feat/csv-validation
docs/windows-setup
```

## Pull requests

A pull request should:

- Explain the problem and the proposed solution.
- List the files or modules affected.
- Include clear testing steps and results.
- Update documentation when behaviour or configuration changes.
- Avoid unrelated formatting or generated-file changes.
- Confirm that no private or sensitive data is included.

Maintainers may request changes before merging. Submission of a contribution means you agree that it may be distributed under the repository's Apache License 2.0.

## Bug reports

Include:

- BIOSYNC version or commit.
- Windows and Python versions.
- Relevant module or workflow.
- Steps to reproduce.
- Expected and actual behaviour.
- Sanitized logs or screenshots.

Never include real student records, attendance exports, credentials, tokens, or private contact information.

## Feature requests

Describe the user problem first, then the proposed feature. Explain who benefits, how the feature fits the existing architecture, and any security or privacy implications.

## Code standards

- Prefer clear, maintainable Python over clever shortcuts.
- Use descriptive names and small functions.
- Validate external input and handle expected failures.
- Avoid hard-coded credentials, machine-specific paths, and personal contact data.
- Add comments only where the reasoning is not obvious from the code.

## Community expectations

Participation in this project is governed by the Code of Conduct. Security vulnerabilities should be reported according to `SECURITY.md`, not through a public issue.
