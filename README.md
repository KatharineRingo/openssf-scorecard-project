# OpenSSF Scorecard Showcase

[![OpenSSF Best Practices](https://www.bestpractices.dev/assets/svg/badge_passing-9860b212f451f2868ff1c05d762e153b6fa72e5050f28325a7457d59b20e0ffb.svg)](https://www.bestpractices.dev/en)
[![OpenSSF Scorecard](https://api.securityscorecards.dev/projects/github.com/KatharineRingo/openssf-scorecard-project/badge)](https://securityscorecards.dev/viewer/?repo=github.com/KatharineRingo/openssf-scorecard-project)

Welcome to Katharine Ringo's software security and OpenSSF Scorecard demonstration project.

## Project Purpose
This repository serves as a security posture demonstration utilizing OpenSSF Scorecard and OpenSSF Best Practices. It implements automated CI/CD security scanning, dependency maintenance, strict token permissions, and security reporting policies.

## Security Practices Implemented
- **OpenSSF Scorecard Automation**: Automated weekly supply chain security scans and code scanning SARIF integration.
- **Least-Privilege Token Permissions**: Workflows explicitly limit default `GITHUB_TOKEN` scopes to `read-all` or job-level minimums.
- **Pinned Dependencies**: Workflow dependencies pinned to verified commit SHAs.
- **Vulnerability Disclosure Policy**: Formal [SECURITY.md](SECURITY.md) guidelines for responsible reporting.
- **Automated Dependency Updates**: Configured [Dependabot](.github/dependabot.yml) for GitHub Actions.
- **Open Source Licensing**: Permissive [MIT License](LICENSE).

## Repository Badges
- **OpenSSF Scorecard**: Evaluates automated security posture across supply chain checks.
- **OpenSSF Best Practices**: Verifies project adheres to Linux Foundation open source security best practices.
