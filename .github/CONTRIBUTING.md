# 🤝 Contribution Guidelines for CloudCostControl-Global-FreeTier-SaaS-PaaS-IaaS-Awesome-List

As the Apex Technical Authority, we uphold the highest standards of collaboration, precision, and technical excellence. This repository is a living document serving the global DevOps and Cloud Architecture community. Adherence to these guidelines ensures the integrity and longevity of this critical resource.

## 1. Philosophy & Core Principles

We build for the future based on **Zero-Defect, High-Velocity, Future-Proof** engineering principles. All contributions must align with:

*   **DRY (Don't Repeat Yourself):** Ensure lists are deduplicated and standardized.
*   **SOLID:** Maintain architectural clarity, even in an Awesome List format (e.g., consistent categorization).
*   **YAGNI (You Ain't Gonna Need It):** Avoid speculative additions; focus on currently available, functional free tiers.

## 2. The Collaboration Workflow

All contributions must follow a structured process to maintain list quality and prevent systemic errors.

1.  **Fork the Repository:** Create your own copy of `chirag127/CloudCostControl-Global-FreeTier-SaaS-PaaS-IaaS-Awesome-List`.
2.  **Branch:** Create a feature branch from `main` for your changes:
    bash
    git checkout -b feature/add-new-service-name
    
3.  **Commit:** Make atomic, clear commits that precisely describe the addition or correction. Use conventional commits where applicable (e.g., `feat: Add new XYZ PaaS offering`).
4.  **Verify:** Before submission, ensure your additions comply with the required metadata schema (Name, Category, Free Tier Details, Link).
5.  **Push:** Push your branch to your forked repository.
6.  **Pull Request (PR):** Open a Pull Request targeting the `main` branch of `chirag127/CloudCostControl-Global-FreeTier-SaaS-PaaS-IaaS-Awesome-List`.

## 3. Pull Request (PR) Requirements

Every Pull Request **MUST** conform to the following criteria, validated by automated checks and peer review.

### A. Mandatory PR Template Use

Use the provided PR Template (`.github/PULL_REQUEST_TEMPLATE.md`). Ensure you explicitly detail:

*   **What was added/changed?** (List the specific service(s) or correction(s).)
*   **Why does it belong?** (Justification based on the free-tier criteria.)
*   **Architectural Compliance Check:** Confirm that the entry adheres to established formatting standards.

### B. Review Process

*   **Automated Checks:** Your PR must pass all checks initiated by `.github/workflows/ci.yml` (Linter checks, Markdown validation, etc.).
*   **Maintainer Review:** A maintainer will review the structure, accuracy, and formatting. Be prepared to iterate based on feedback.

## 4. Reporting Issues (Bug Reports & Service Degradation)

If you discover a broken link, an outdated free-tier policy, or a service that no longer qualifies:

1.  **DO NOT** open an issue labeled `bug` unless it concerns the repository structure or build process itself.
2.  **Preferred Action (List Maintenance):** Open a Pull Request immediately with the correction, referencing the outdated information.
3.  **If an Issue Must Be Opened:** Use the provided template (`.github/ISSUE_TEMPLATE/bug_report.md`). Clearly label the service, provide the current status, and cite the official source confirming the change.

## 5. Repository Security & Trust

We take the integrity of this community resource seriously. If you discover a security vulnerability in the repository structure, CI/CD pipeline, or documentation generation process, please follow the established Security Policy immediately:

*   Refer to: **[SECURITY.md](https://github.com/chirag127/CloudCostControl-Global-FreeTier-SaaS-PaaS-IaaS-Awesome-List/security/advisories)**

## 6. Code of Conduct

This project adheres to the Contributor Covenant Code of Conduct. We expect all participants to interact respectfully and constructively. Harassment or abusive language will result in immediate removal from contribution privileges.

--- 

*This document is governed by the same principles of clarity and precision applied to the list contents. For deeper technical alignment, consult the **AGENTS.md** file.*