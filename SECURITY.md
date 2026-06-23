# Security Policy

## Supported Versions

Security updates are currently provided for the following versions of this project:

| Version | Supported |
| ------- | --------- |
| 5.1.x   | ✅        |
| 5.0.x   | ❌        |
| 4.0.x   | ✅        |
| < 4.0   | ❌        |

Only supported versions will receive security patches, fixes, or vulnerability-related updates.

## Reporting a Vulnerability

If you discover a security vulnerability in this project, please report it responsibly.

### How to Report

Please do **not** open a public GitHub issue for security vulnerabilities.

Instead, report the vulnerability using one of the following methods:

- Use GitHub Security Advisories, if enabled for this repository.
- Or contact the project maintainer privately through the official contact channel listed in the repository.

When reporting a vulnerability, please include:

- A clear description of the vulnerability.
- Steps to reproduce the issue.
- The affected version or commit.
- Any proof-of-concept code, logs, screenshots, or technical details.
- The possible impact of the vulnerability.
- Suggested fixes, if available.

## Response Timeline

After a vulnerability is reported, you can expect the following process:

| Stage | Expected Time |
| ----- | ------------- |
| Initial acknowledgement | Within 3–7 days |
| Initial review | Within 7–14 days |
| Fix planning | Depending on severity |
| Security patch release | As soon as reasonably possible |

Response time may vary depending on the complexity and severity of the issue.

## Vulnerability Handling Process

Once a report is received:

1. The maintainer will review and verify the vulnerability.
2. If the vulnerability is accepted, it will be assigned a severity level.
3. A fix will be prepared for supported versions.
4. A patched release will be published.
5. A public disclosure or security advisory may be issued after the fix is available.

If the report is declined, the maintainer will explain the reason when possible.

## Disclosure Policy

Please allow the maintainer reasonable time to investigate and fix the issue before public disclosure.

Do not publicly disclose the vulnerability until:

- A fix has been released, or
- The maintainer has agreed to disclosure, or
- A reasonable coordinated disclosure period has passed.

## Scope

The following are considered in scope:

- Authentication or authorization bypass.
- Remote code execution.
- Injection vulnerabilities.
- Sensitive data exposure.
- Privilege escalation.
- Dependency-related security issues.
- Any issue that may compromise user data, system integrity, or project security.

The following are generally out of scope:

- Spam or social engineering.
- Issues requiring physical access to a user’s device.
- Vulnerabilities in unsupported versions.
- Reports without enough information to reproduce.
- Denial-of-service issues without demonstrated practical impact.

## Safe Harbor

Security researchers who report vulnerabilities responsibly and in good faith will not be penalized for their research, provided they:

- Do not exploit the vulnerability beyond what is necessary to prove its existence.
- Do not access, modify, delete, or exfiltrate user data.
- Do not disrupt services or systems.
- Do not publicly disclose the issue before coordination with the maintainer.

## Security Updates

Security updates will be released through normal GitHub releases, commits, or advisories.

Users are encouraged to keep their installations updated to the latest supported version.
