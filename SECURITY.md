# Security Policy

## Supported Versions

Security updates are provided for the latest release of `automerge-action`.

| Version | Supported |
| --- | --- |
| Latest release | Yes |
| Older releases | No |

If you are using an older release, please upgrade to the latest version before reporting a vulnerability.

## Reporting a Vulnerability

Please **do not report security vulnerabilities through public GitHub issues, pull requests, or discussions**.

Use GitHub's **Private Vulnerability Reporting** or **Security Advisories** to report a vulnerability privately.

When reporting a vulnerability, please include:

- A clear description of the vulnerability.
- The affected version or commit.
- Steps to reproduce the issue.
- A minimal proof of concept, where practical.
- The potential security impact.
- Any suggested mitigation or fix.

Please avoid including real credentials, access tokens, personal data, or other sensitive information in the report.

## Scope

Security issues of particular interest include vulnerabilities that could allow an attacker to:

- Cause the action to merge a pull request when its configured conditions are not satisfied.
- Bypass repository or pull request security controls.
- Obtain or expose GitHub tokens, credentials, or other secrets.
- Execute unintended commands or code on the GitHub Actions runner.
- Exploit untrusted pull request or repository data.
- Cause the action to access repositories, resources, or GitHub API operations beyond its intended permissions.
- Compromise the action through a dependency or GitHub Action supply-chain attack.
- Tamper with the generated `dist` files or released action code in a way that affects users.

## Out of Scope

The following are generally not considered security vulnerabilities unless they result in a security impact:

- Bugs that do not affect confidentiality, integrity, or availability.
- Configuration mistakes in a user's own workflow.
- Vulnerabilities in GitHub Actions or GitHub itself that cannot be demonstrated to affect `automerge-action`.
- Vulnerabilities in third-party dependencies that do not affect `automerge-action`.

## Disclosure

Please allow reasonable time for a vulnerability to be investigated and, where appropriate, fixed before public disclosure.

We will work with the reporter to understand the issue, develop a fix, and coordinate disclosure where appropriate.

Security fixes may be released as a new version of `automerge-action`, together with appropriate release notes.

## Security Practices

The project uses automated security controls including dependency vulnerability scanning, static analysis, automated testing, and GitHub Actions security checks.

GitHub Actions used by the project are pinned to specific commit SHAs where practical, and workflow permissions follow the principle of least privilege.

The generated `dist` files are committed because GitHub Actions execute the action from the repository. Changes to generated distribution files should correspond to changes in the source and build process.
