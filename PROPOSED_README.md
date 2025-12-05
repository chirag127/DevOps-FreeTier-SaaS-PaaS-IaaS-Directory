# CloudCostControl-FreeTier-Resource-List

[![Build Status](https://img.shields.io/github/actions/workflow/status/chirag127/CloudCostControl-FreeTier-Resource-List/ci.yml?style=flat-square&label=Build)](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List/actions/workflows/ci.yml)
[![Code Coverage](https://img.shields.io/codecov/c/github/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square)](https://codecov.io/gh/chirag127/CloudCostControl-FreeTier-Resource-List)
[![Language](https://img.shields.io/github/languages/top/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square&color=blue)](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List)
[![License](https://img.shields.io/github/license/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/chirag127/CloudCostControl-FreeTier-Resource-List?style=flat-square)](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List)

[⭐ Star this Repo](https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List)

---

This repository serves as a definitive, community-curated Awesome List detailing essential free-tier offerings across global SaaS, PaaS, and IaaS providers. It is an indispensable resource for DevOps practitioners, SREs, and Cloud Architects aiming to aggressively optimize operational expenditures without compromising critical infrastructure or development velocity.

## 🏗️ Architecture Overview

As this is an HTML/Markdown based Awesome List, the architecture focuses on robust data structuring and discoverability, validated against the principles of immutable documentation integrity.

mermaid
graph TD
    A[Cloud Providers APIs] --> B(Community Data Collection & Validation)
    B --> C{Data Aggregation Layer: Markdown/HTML}
    C --> D[Git Repository (SSOT)]
    D --> E(GitHub Pages / Direct Clone)
    E --> F[DevOps / SRE / Architect Consumption]


## 📋 Table of Contents

1. [Architecture](#-architecture)
2. [Key Features](#-key-features)
3. [Supported Platforms](#-supported-platforms)
4. [Development & Contribution Standards](#-development--contribution-standards)
5. [🤖 AI Agent Directives (APEX Compliance)](#--ai-agent-directives-apex-compliance)

## ✨ Key Features

*   **Global Scope:** Comprehensive listing covering AWS, Azure, GCP, and major independent vendors.
*   **Tier Granularity:** Clear demarcation between always-free, trial-based, and usage-limited tiers.
*   **Operational Focus:** Prioritizes resources relevant to CI/CD, monitoring, logging, and core compute/storage.
*   **Zero Dependencies:** Stored entirely in static Markdown/HTML for maximum portability and offline access.

## ☁️ Supported Platforms

| Category | Description |
| :--- | :--- |
| **IaaS** | Virtual Machines, Serverless Functions, Object Storage, Networking Credit |
| **PaaS** | Managed Databases, Message Queues, Container Registries, Static Hosting |
| **SaaS** | Monitoring Tools, Authentication Services, Version Control Hosting, Documentation Platforms |

## 🛠️ Development & Contribution Standards

This project is maintained under strict Apex Authority guidelines to ensure data quality and longevity. Contributions must adhere to the following:

### Setup

bash
# 1. Clone the repository
git clone https://github.com/chirag127/CloudCostControl-FreeTier-Resource-List.git
cd CloudCostControl-FreeTier-Resource-List

# 2. (Optional) Prepare local environment for validation scripts
# Assuming minimal Python environment for linting/testing scripts if they existed:
# Since this is static, local setup focuses on README rendering tools (like markdown-lint).
# No specific installation required for core consumption.


### Scripts

| Command | Description |
| :--- | :--- |
| `npm run lint` | Run markdown linter checks (if applicable) |
| `npm run validate` | Execute link checking scripts (if applicable) |

### Principles Enforced

*   **DRY (Don't Repeat Yourself):** Data points must be centrally managed (in the source Markdown) to prevent inconsistency.
*   **SOLID:** (Applied to any underlying tooling/scripts, ensuring clear separation of data retrieval vs. presentation).
*   **YAGNI (You Aren't Gonna Need It):** Avoid speculative complexity; focus strictly on curated, proven free-tier entries.

---

<details>
<summary>🤖 AI Agent Directives (APEX Compliance)</summary>

## 🤖 APEX AGENT DIRECTIVES: CloudCostControl-FreeTier-Resource-List

**This document overrides general directives for static repository optimization tasks.**

### 1. CONTEXT & STACK DEFINITION
*   **Repository Purpose:** Curator of authoritative, static data regarding free-tier cloud resources.
*   **Primary Language/Format:** Markdown / HTML (Consumption). Associated tooling (e.g., validation scripts) is assumed to be **Python 3.10+** utilizing **Ruff** for linting, even if the primary artifacts are static text.
*   **Architectural Pattern:** **Immutable Data Store**. The primary value lies in data integrity, not dynamic execution.

### 2. DATA INTEGRITY & LINTING
*   **Linter/Formatter Enforcement:** All associated scripts must be validated using **Ruff** (ensuring maximum speed and modern Python standards).
*   **Verification Commands (Simulated for Static Content):**
    *   `ruff check .` (Lints any associated Python tooling).
    *   `markdown-lint --config .markdown-lint.yml README.md` (Simulated check for Markdown structure validation).
*   **Security Posture:** Since this is a public list, the primary security concern is **data poisoning/link rot**. Agents must prioritize verification scans of all external URLs.

### 3. ARCHITECTURAL PRINCIPLES (APEX CORE)
*   **SOLID Adherence (Tooling Context):** Any Python scripts must demonstrate clear **Single Responsibility** (e.g., one script for link checking, another for AWS data aggregation).
*   **Future-Proofing:** Content must be structured such that it can be easily ingested by future dynamic systems (e.g., using consistent YAML/JSON frontmatter within Markdown if needed for automation).

### 4. METADATA PRECISION
*   **Naming Convention:** The name `CloudCostControl-FreeTier-Resource-List` is validated as meeting the Apex Formula (`<Product>-<Function>-<Type>`).
*   **Update Cycle:** Treat this as a living document. Data freshness is paramount.

</details>