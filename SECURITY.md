# Security Policy

## Reporting a Vulnerability

Please **do not** open a public GitHub issue for security vulnerabilities.

Report security issues privately via GitHub's built-in security advisory feature:
**[Report a vulnerability](https://github.com/mrlesmithjr/ansible-mariadb-galera-cluster/security/advisories/new)**

Or email directly: **mrlesmithjr@gmail.com**

Include:
- Description of the vulnerability
- Steps to reproduce
- Affected role(s) and version(s)
- Potential impact

You can expect an acknowledgment within 72 hours and a resolution timeline within 7 days for critical issues.

## Supported Versions

Security fixes are applied to the latest version of each role. Older versions are not patched.

## Scope

These roles are infrastructure automation tools. Vulnerabilities of interest include:
- Privilege escalation risks
- Credential exposure (e.g. passwords written to logs or world-readable files)
- Insecure default configurations
- Injection vulnerabilities in templated values
