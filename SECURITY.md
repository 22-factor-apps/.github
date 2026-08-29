# Security policy

Use GitHub private vulnerability reporting in the affected repository for
issues that could expose credentials, private repository metadata, assessment
evidence, build provenance, or deployment behavior. Do not put sensitive proof
or live tokens in a public issue.

For the methodology site, report content-integrity, dependency, build, or Pages
deployment issues in `22-factor-apps.github.io`. For the Rust auditor, report
credential handling, path disclosure, network, parsing, or output-validation
issues in `22-factor-apps-audit`.

The latest tagged release and current `main` branch are supported. Maintainers
will acknowledge a private report, establish an impact boundary, and coordinate
disclosure after a fix or explicit risk decision is available.
