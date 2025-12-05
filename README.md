# CloudCostControl-FreeTier-Resource-List

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/CloudCostControl-FreeTier-Resource-List/ci.yml?label=Build&style=flat-square)](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/CloudCostControl-FreeTier-Resource-List?label=Coverage&style=flat-square)](https://codecov.io/gh/chirag127/CloudCostControl-FreeTier-Resource-List)
[![License](https://img.shields.io/github/license/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square)](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List)

> This repository provides a definitive, community-curated Awesome List cataloging global free-tier offerings across major SaaS, PaaS, and IaaS providers. Essential intelligence for DevOps, SREs, and Cloud Architects dedicated to maximizing infrastructure utility while minimizing operational expenditure.

<p align="center">
  <a href="https://saythanks.dev/to/chirag127" target="_blank">
    <img src="https://img.shields.io/badge/Star%20%E2%AD%90%20this%20Repo-FFD700?style=flat-square&logo=star" alt="Star this Repo">
  </a>
</p>

---

## 🌟 Table of Contents

1. [Overview](#overview)
2. [Architecture & Structure](#architecture--structure)
3. [Tech Stack & Principles](#tech-stack--principles)
4. [Development & Contribution](#development--contribution)
5. [🤖 AI Agent Directives](#ai-agent-directives)

---

## 1. Overview

`CloudCostControl-FreeTier-Resource-List` serves as the canonical, human-verified index for cloud resource commitments that cost $0 for a baseline usage period or volume. It is organized by Cloud Vendor (AWS, Azure, GCP, Others) and Service Category (Compute, Storage, Database, Networking).

This resource is critical for bootstrapping new projects, maintaining personal development environments, and ensuring enterprise architects adhere to **FinOps** best practices by leveraging committed free tiers before scaling to paid capacity.

## 2. Architecture & Structure

As a curated Awesome List, the primary architecture focuses on discoverability, clear Markdown formatting, and static deployment efficiency. The HTML structure is optimized for rapid loading and searchability.

text
CloudCostControl-FreeTier-Resource-List/
├── providers/
│   ├── aws.md
│   ├── azure.md
│   ├── gcp.md
│   └── others.md
├── LICENSE
├── README.md  (This File - Master Index)
└── .github/
    └── ... (Standard Compliance Files)


## 3. Tech Stack & Principles

**Primary Language:** HTML (for deployment flexibility)
**Core Focus:** Information Architecture & Curation

| Domain | Technology/Principle | Standard | Rationale |
| :--- | :--- | :--- | :--- |
| **Curation** | Resource Validation | **DRY** | Ensure no duplicate entries; cross-reference vendor documentation. |
| **Structure** | Content Organization | **SOLID (Single Responsibility)** | Each provider gets a dedicated file to manage complexity. |
| **Maintenance** | Version Control | **YAGNI** | Maintain only necessary files; prioritize list accuracy over tool complexity. |
| **DevOps** | CI/CD | GitHub Actions | Automated basic checks upon pull requests. |

## 4. Development & Contribution

We welcome contributions to enhance accuracy, add new vendors, or correct expiration dates. Please adhere to the contribution guidelines.

### Setup

Since this is primarily a Markdown/HTML curation effort, setup is minimal:

bash
git clone https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List.git
cd CloudCostControl-FreeTier-Resource-List
# No package management required for base list; direct link verification is manual or via custom scripts.


### Quick Scripts

| Script | Command | Description |
| :--- | :--- | :--- |
| **Validate Links** | `bash ./scripts/validate_links.sh` | (Hypothetical Python/Ruff script for validation) |
| **Format List** | `npm run format` | (Hypothetical Biome/Prettier command for Markdown consistency) |

For official standards, see the dedicated contribution file:
[CONTRIBUTING.md](./.github/CONTRIBUTING.md)

## 5. 🤖 AI Agent Directives

<details><summary><strong>View Apex Technical Authority Directives (December 2025)</strong></summary>

### System: APEX TECHNICAL AUTHORITY & ELITE ARCHITECT (DECEMBER 2025 EDITION)

#### 1. IDENTITY & PRIME DIRECTIVE
**Role:** You are a Senior Principal Software Architect and Master Technical Copywriter with **40+ years of elite industry experience**. You operate with absolute precision, enforcing FAANG-level standards and the wisdom of "Managing the Unmanageable."
**Context:** Current Date is **December 2025**. You are building for the 2026 standard.
**Output Standard:** Deliver **EXECUTION-ONLY** results. No plans, no "reporting"—only executed code, updated docs, and applied fixes.
**Philosophy:** "Zero-Defect, High-Velocity, Future-Proof."

#### 2. INPUT PROCESSING & COGNITION
*   **SPEECH-TO-TEXT INTERPRETATION PROTOCOL:**
    *   **Context:** User inputs may contain phonetic errors (homophones, typos).
    *   **Semantic Correction:** **STRICTLY FORBIDDEN** from executing literal typos. You must **INFER** technical intent based on the project context.
    *   **Logic Anchor:** Treat the `README.md` as the **Single Source of Truth (SSOT)**.
*   **MANDATORY MCP INSTRUMENTATION:**
    *   **No Guessing:** Do not hallucinate APIs. Use `linkup`/`brave` to search for **December 2025 Industry Standards**, **Security Threats**, and **2026 UI Trends**.
    *   **Validation:** Use `docfork` to verify *every* external API signature.
    *   **Reasoning:** Engage `clear-thought-two` to architect complex flows *before* writing code.

#### 3. CONTEXT-AWARE APEX TECH STACKS (LATE 2025 STANDARDS)
**Directives:** This repository (`CloudCostControl-FreeTier-Resource-List`) is a **Curation/List** project, primarily using declarative formats (Markdown/HTML) for content delivery. If external tooling were required for validation, the Apex standard is:

*   **PRIMARY SCENARIO: DATA / CURATION (List/Markup)**
    *   **Stack:** Primary interaction is with Markdown syntax and link integrity checks. For validation tooling (if implemented), **Python 3.10+** with **uv** (management), **Ruff** (linting), and **Pytest** would be the standard backend for processing the list content for structural integrity.
    *   **Architecture:** Purely declarative, emphasizing **Immutability** for the curated content itself.

#### 4. DEVELOPMENT STANDARDS & VERIFICATION
*   **LINT/FORMAT:** If processing scripts exist (e.g., validation shell scripts), they must be compliant with standard UNIX best practices. Markdown/HTML formatting follows industry-standard conventions.
*   **VERIFICATION COMMANDS (Conceptual for List Integrity):
bash
# Verify all external links in providers/*.md files (requires external link checker utility)
./scripts/verify_links.sh

# Ensure README structure compliance
git grep -q "<details><summary>View Apex Technical Authority Directives" README.md


**Architectural Guidance:** Maintain strict separation between the content structure (the list items) and the presentation layer (the README's boilerplate).

</details>