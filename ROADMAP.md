# BIOSYNC Roadmap

This roadmap describes intended open-source improvements. It is not a promise of delivery dates.

## Near term

- Add automated tests for attendance parsing, duplicate handling, date ranges, and report calculations.
- Provide a sample configuration that contains no credentials or institution-specific data.
- Add synthetic demonstration data and a safe local demo workflow.
- Improve validation and error messages for CSV, XLS, and XLSX inputs.
- Document Windows setup, device connectivity, WhatsApp automation, and recovery services more clearly.
- Add structured logging and safer log redaction.

## Reliability

- Expand tests for network recovery and browser-session recovery.
- Improve idempotency when jobs restart after failure.
- Add health checks for scheduled tasks and device ingestion.
- Reduce hard-coded paths and machine-specific configuration.

## Security and privacy

- Move all sensitive configuration to environment variables or ignored local configuration.
- Add automated secret scanning and dependency checks.
- Provide guidance for data retention, backup protection, and access control.
- Add tools for anonymizing diagnostic exports.

## Contributor experience

- Label beginner-friendly and help-wanted issues.
- Add issue and pull-request templates.
- Document the architecture of major modules.
- Publish versioned releases and changelogs.
- Define a test matrix for supported Python and Windows versions.

## Longer term

- Provide optional database-backed storage behind a documented interface.
- Support additional biometric device adapters through a plugin-style architecture.
- Add a web-based monitoring dashboard that does not expose personal attendance data.
- Improve localization and accessibility for reports.
