# Acceptable Contributions

This project welcomes contributions that improve the reliability, security, maintainability, documentation, accessibility, or usability of the project.

## Acceptable contributions

The following types of contributions are welcome:

- **Bug fixes** that address reproducible problems without introducing unrelated changes.
- **Security improvements**, including fixes for vulnerabilities, insecure defaults, unsafe dependencies, or weaknesses identified through security tooling.
- **Dependency updates** that address security issues, compatibility problems, or reasonable maintenance needs.
- **Tests** that improve coverage or prevent regressions.
- **Performance improvements** where there is a demonstrable benefit and the change remains maintainable.
- **Documentation improvements**, including corrections, clarifications, examples, and usage guidance.
- **Build and CI improvements** that make development, testing, security scanning, or releases more reliable.
- **Accessibility improvements** that make the project easier to use or contribute to.
- **Code quality improvements** that improve readability, maintainability, or consistency without unnecessarily changing behaviour.
- **Feature additions** that are relevant to the project's purpose and have been discussed or agreed upon where appropriate.

## Contribution requirements

Contributions should:

1. Be relevant to the purpose and scope of the project.
2. Be focused on a clear problem or improvement.
3. Avoid unnecessary changes to unrelated files or functionality.
4. Include appropriate tests when behaviour or functionality changes.
5. Keep documentation up to date when user-facing behaviour changes.
6. Pass the project's formatting, linting, testing, and build checks.
7. Follow the project's existing coding and contribution conventions.
8. Avoid introducing unnecessary dependencies.
9. Preserve existing security and privacy protections.
10. Be submitted in good faith and with sufficient information for maintainers to review the change.

## Security-related contributions

Security vulnerabilities should not normally be disclosed through a public issue or pull request.

Please follow the project's security policy for reporting vulnerabilities privately.

Contributions that improve the project's security posture are encouraged, including:

- Removing vulnerable dependencies.
- Updating dependencies to supported fixed versions.
- Improving GitHub Actions permissions.
- Pinning third-party GitHub Actions appropriately.
- Improving dependency and supply-chain security.
- Improving security scanning and vulnerability detection.
- Improving release integrity and provenance.
- Removing unnecessary secrets, credentials, or sensitive information from source code and workflows.

Security changes should be narrowly scoped and should not weaken existing security controls merely to make a build or workflow pass.

## GitHub Actions and CI contributions

Changes to workflows must preserve the principle of least privilege.

Contributors should:

- Grant only the permissions required by a workflow.
- Avoid exposing write-capable credentials to untrusted pull-request code.
- Avoid using secrets unnecessarily.
- Prefer maintained and appropriately pinned actions.
- Ensure workflows continue to work for pull requests originating from forks.
- Avoid disabling security checks solely to resolve a failing build.
- Keep automated formatting, linting, testing, and build checks working.

Any workflow that modifies repository contents or pushes commits must be reviewed particularly carefully.

## Pull requests

Pull requests should explain:

- What has changed.
- Why the change is needed.
- How the change was tested.
- Any security, compatibility, or behavioural implications.

Small, focused pull requests are preferred over large changes that combine unrelated fixes or features.

Maintainers may request changes, decline contributions, or ask that a proposal be discussed before implementation.

## Unacceptable contributions

The project will not accept contributions that:

- Introduce malicious code or intentionally harmful behaviour.
- Deliberately weaken security controls without a justified and reviewed reason.
- Expose credentials, secrets, personal information, or other sensitive data.
- Introduce known vulnerable dependencies without a compelling and documented reason.
- Circumvent project security, testing, or review requirements.
- Contain discriminatory, abusive, threatening, or harassing content.
- Facilitate illegal activity.
- Deliberately introduce backdoors, spyware, malware, or other harmful functionality.
- Make unrelated changes solely to increase the size or complexity of a pull request.
- Violate applicable licences, copyrights, or other intellectual-property rights.
- Misrepresent the purpose, origin, testing, or security properties of a contribution.

## Maintainer discretion

Acceptance of a contribution is ultimately at the discretion of the project maintainers.

Maintainers may reject or request changes to contributions that technically work but are inconsistent with the project's goals, architecture, security requirements, maintenance burden, or long-term direction.

The absence of a specific prohibition in this document does not require the project to accept a contribution.

## Changes to this policy

This document may be updated as the project evolves. Changes should preserve the project's commitment to open, constructive, secure, and maintainable contributions.
