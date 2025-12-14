# Portfolio

Navigation hub for C-Tech-Labs projects, templates, and documentation. Curated for engineers who design, build, and operate software across multiple languages and domains.

## Table of Contents
- [Core Focus](#core-focus)
- [Featured Projects](#featured-projects)
- [Platform & Cloud](#platform--cloud)
- [Automation & Tooling](#automation--tooling)
- [Security & Compliance](#security--compliance)
- [Learning Labs](#learning-labs)
- [Runbooks & Documentation](#runbooks--documentation)
- [Engineering Standards](#engineering-standards)
- [Getting Started](#getting-started)
- [Contact](#contact)

## Core Focus
- **Multi-language delivery** – Python, TypeScript/Node.js, Go, and Bash for automation and services.
- **Cloud-first architecture** – AWS reference patterns with Terraform and GitHub Actions.
- **Operational excellence** – Health checks, runbooks, and repeatable templates.

## Featured Projects
- **iac-aws-landing-zone** – Enterprise-grade AWS landing zone baseline with account structure, networking, security modules, and policies.
- **tool-nxwitness-healthcheck** – Python CLI that automates health checks for Nx Witness VMS and camera systems.
- **lab-terraform-modules** – Collection of reusable Terraform modules for experiments and internal labs.
- **template-python-cli** – Starter template for building standardized Python CLI tools with GitHub Actions.

## Platform & Cloud
- **iac-aws-landing-zone** – Baseline for multi-account AWS landing zone, guardrails, and central logging.
- **lab-terraform-modules** – Library of reusable Terraform modules covering networking, IAM, and observability.

## Automation & Tooling
- **tool-nxwitness-healthcheck** – Health check CLI for Nx Witness and camera ecosystems with reporting outputs.
- **template-python-cli** – Opinionated template with packaging, linting, testing, and release workflows.
- **template-typescript-service** – Service bootstrap with Express, ESLint/Prettier, and GitHub Actions CI.

## Security & Compliance
- **iac-aws-landing-zone** – Security baseline modules, SCPs, IAM boundaries, and detective controls.
- **sec-policy-templates** – Sample security policies, compliance mappings, and audit-ready artifacts.

## Learning Labs
- **lab-terraform-modules** – Learning modules for infrastructure as code with Terraform, including hands-on scenarios.
- **lab-observability** – Traces, metrics, and logs playground with OpenTelemetry and Prometheus/Grafana.

## Runbooks & Documentation
- **doc-runbooks** – Operational runbooks for platform teams and SRE rotations.
- **doc-architecture** – Reference architectures, ADRs, and implementation notes.

## Engineering Standards
- **Coding practices** – Enforce linting, typing, and automated tests across repos (Python: `ruff`, `mypy`; TypeScript: `eslint`, `tsc`).
- **CI/CD** – GitHub Actions pipelines for build, test, security scans, and artifact publishing.
- **IaC hygiene** – `terraform fmt`, `terraform validate`, drift detection, and pre-commit hooks.
- **Observability** – Standardized logging, metrics, and tracing instrumentation guidance.

## Getting Started
1. Clone the target repository (e.g., `git clone https://github.com/C-Tech-Labs/<project>.git`).
2. Review the project-level README for prerequisites and environment setup.
3. Run formatting and tests locally before opening a PR:
   - Python: `make lint test` (ruff, mypy, pytest)
   - TypeScript: `npm run lint && npm test`
   - Terraform: `terraform fmt -check && terraform validate`
4. Open a feature branch and follow the contribution guide in each repo.

## Contact
- **Team**: C-Tech-Labs Platform Engineering
- **Email**: platform@c-tech-labs.com
- **Chat**: Internal Slack `#platform-eng`
