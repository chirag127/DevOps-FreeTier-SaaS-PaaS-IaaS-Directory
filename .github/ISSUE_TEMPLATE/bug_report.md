---
name: "🐛 Data Integrity Report (Bug)"
about: Report a factual error, broken link, retired service, or outdated detail in the Awesome List.
title: "[BUG] Detailed description of the outdated entry"
labels: ['type:bug', 'status:triage', 'area:data-integrity']
assignees: []
---

## 🛑 Apex Quality Control: Data Integrity Report

Thank you for helping maintain the accuracy and value of the `CloudCostControl-Global-FreeTier-SaaS-PaaS-IaaS-Awesome-List`. Use this template to report factual errors, broken links, or misleading service details. High-quality data integrity is crucial for cost optimization.

---

### 1. Location of the Issue

Please provide the exact location of the error within the list. Triage is significantly faster with precise coordinates.

- [ ] I have verified the issue persists in the `main` branch.
- **Section/Category:** (e.g., AWS Free Tier, Database Services, Monitoring, Serverless Compute)
- **Specific Service Name:** (e.g., MongoDB Atlas, Cloudflare Workers, Redis Cloud)
- **Direct Link/Anchor Tag (if applicable):** [Paste the URL or line number/anchor tag reference here]

### 2. Detailed Description of the Failure

Provide a clear and concise description of what the current list entry says, and what the correct status should be.

**A. Current Status (The Bug):**
*Example: The list states that Service X offers 5GB free storage, but their current public documentation now says 1GB.*

**B. Expected/Corrected Status (The Fix):**
*Example: Service X free tier has been reduced to 1GB storage, or the original link provided is resulting in a 404 error.*

### 3. Proof and Verification

The Apex standard requires verifiable evidence for all data updates. Please link directly to the official documentation, pricing page, or announcement that verifies the error.

- **Verification URL:** [Paste link to official documentation confirming the change]
- **Date Verified:** (YYYY-MM-DD)

### 4. Impact Assessment

How significant is this inaccuracy? This helps prioritize the fix for users dependent on cost-critical data.

- [ ] High (Service is completely retired/link is 404/major price change rendering the service non-free)
- [ ] Medium (Minor tier adjustment/outdated documentation link or non-critical feature change)
- [ ] Low (Typo/Stylistic issue that doesn't affect cost or accessibility)

### 5. Environment (If applicable)

If the issue relates to viewing or accessing the list (e.g., formatting errors):

- **Browser & Version:** (e.g., Chrome 120, Firefox 118)
- **Operating System:** (e.g., macOS Sonoma, Windows 11)
- **Device Type:** (Desktop, Mobile)