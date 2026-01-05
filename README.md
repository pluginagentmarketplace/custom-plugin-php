<div align="center">

<!-- Animated Typing Banner -->
<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=2E9EF7&center=true&vCenter=true&multiline=true&repeat=true&width=600&height=100&lines=Php+Assistant;7+Agents+%7C+7+Skills;Claude+Code+Plugin" alt="Php Assistant" />

<br/>

<!-- Badge Row 1: Status Badges -->
[![Version](https://img.shields.io/badge/Version-1.0.0-blue?style=for-the-badge)](https://github.com/pluginagentmarketplace/custom-plugin-php/releases)
[![License](https://img.shields.io/badge/License-Custom-yellow?style=for-the-badge)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Production-brightgreen?style=for-the-badge)](#)
[![SASMP](https://img.shields.io/badge/SASMP-v1.3.0-blueviolet?style=for-the-badge)](#)

<!-- Badge Row 2: Content Badges -->
[![Agents](https://img.shields.io/badge/Agents-7-orange?style=flat-square&logo=robot)](#-agents)
[![Skills](https://img.shields.io/badge/Skills-7-purple?style=flat-square&logo=lightning)](#-skills)
[![Commands](https://img.shields.io/badge/Commands-4-green?style=flat-square&logo=terminal)](#-commands)

<br/>

<!-- Quick CTA Row -->
[📦 **Install Now**](#-quick-start) · [🤖 **Explore Agents**](#-agents) · [📖 **Documentation**](#-documentation) · [⭐ **Star this repo**](https://github.com/pluginagentmarketplace/custom-plugin-php)

---

### What is this?

> **Php Assistant** is a Claude Code plugin with **7 agents** and **7 skills** for php development.

</div>

---

## 📑 Table of Contents

<details>
<summary>Click to expand</summary>

- [Quick Start](#-quick-start)
- [Features](#-features)
- [Agents](#-agents)
- [Skills](#-skills)
- [Commands](#-commands)
- [Documentation](#-documentation)
- [Contributing](#-contributing)
- [License](#-license)

</details>

---

## 🚀 Quick Start

### Prerequisites

- Claude Code CLI v2.0.27+
- Active Claude subscription

### Installation (Choose One)

<details open>
<summary><strong>Option 1: From Marketplace (Recommended)</strong></summary>

```bash
# Step 1️⃣ Add the marketplace
/plugin marketplace add pluginagentmarketplace/custom-plugin-php

# Step 2️⃣ Install the plugin
/plugin install php-assistant@pluginagentmarketplace-php

# Step 3️⃣ Restart Claude Code
# Close and reopen your terminal/IDE
```

</details>

<details>
<summary><strong>Option 2: Local Installation</strong></summary>

```bash
# Clone the repository
git clone https://github.com/pluginagentmarketplace/custom-plugin-php.git
cd custom-plugin-php

# Load locally
/plugin load .

# Restart Claude Code
```

</details>

### ✅ Verify Installation

After restart, you should see these agents:

```
php-assistant:09-management-design
php-assistant:04-data-analytics
php-assistant:05-ai-ml-mlops
php-assistant:02-backend-servers
php-assistant:08-specialized-tech
... and 4 more
```

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🤖 **7 Agents** | Specialized AI agents for php tasks |
| 🛠️ **7 Skills** | Reusable capabilities with Golden Format |
| ⌨️ **4 Commands** | Quick slash commands |
| 🔄 **SASMP v1.3.0** | Full protocol compliance |

---

## 🤖 Agents

### 7 Specialized Agents

| # | Agent | Purpose |
|---|-------|---------|
| 1 | **09-management-design** | Master product management, leadership, and design discipline |
| 2 | **04-data-analytics** | Master data engineering, analytics, and data science. Covers |
| 3 | **05-ai-ml-mlops** | Master artificial intelligence, machine learning, and MLOps. |
| 4 | **02-backend-servers** | Master server-side development with multiple languages and f |
| 5 | **08-specialized-tech** | Master specialized technologies including blockchain, game d |
| 6 | **03-mobile-crossplatform** | Master mobile app development across iOS, Android, and cross |
| 7 | **07-security-architecture** | Master cybersecurity, system design, and software architectu |
| 8 | **06-cloud-devops-infra** | Master cloud platforms, DevOps practices, and infrastructure |
| 9 | **01-web-frontend** | Master web and frontend development technologies. Covers HTM |

---

## 🛠️ Skills

### Available Skills

| Skill | Description | Invoke |
|-------|-------------|--------|
| `databases` | Master SQL and NoSQL databases. Covers PostgreSQL, MySQL, Mo | `Skill("php-assistant:databases")` |
| `security-practices` | Master security and compliance. Covers OWASP, secure coding, | `Skill("php-assistant:security-practices")` |
| `devops-tools` | Master DevOps tools and practices. Covers Docker, Kubernetes | `Skill("php-assistant:devops-tools")` |
| `cloud-platforms` | Master cloud infrastructure and services. Covers AWS, Google | `Skill("php-assistant:cloud-platforms")` |
| `api-design` | Master API design and development. Covers REST, GraphQL, gRP | `Skill("php-assistant:api-design")` |
| `languages` | Master multiple programming languages including JavaScript,  | `Skill("php-assistant:languages")` |
| `testing-quality` | Master testing strategies and quality assurance. Covers unit | `Skill("php-assistant:testing-quality")` |
| `design-ux` | Master UX/UI design and product design. Covers user research | `Skill("php-assistant:design-ux")` |
| `frameworks-libraries` | Master modern frameworks and libraries. Covers React, Vue, A | `Skill("php-assistant:frameworks-libraries")` |
| `machine-learning` | Master machine learning, deep learning, and AI. Covers algor | `Skill("php-assistant:machine-learning")` |

---

## ⌨️ Commands

| Command | Description |
|---------|-------------|
| `/learn` | /learn |
| `/assess` | /assess |
| `/browse-role` | role |
| `/roadmap` | /roadmap |

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [CHANGELOG.md](CHANGELOG.md) | Version history |
| [CONTRIBUTING.md](CONTRIBUTING.md) | How to contribute |
| [LICENSE](LICENSE) | License information |

---

## 📁 Project Structure

<details>
<summary>Click to expand</summary>

```
custom-plugin-php/
├── 📁 .claude-plugin/
│   ├── plugin.json
│   └── marketplace.json
├── 📁 agents/              # 7 agents
├── 📁 skills/              # 7 skills (Golden Format)
├── 📁 commands/            # 4 commands
├── 📁 hooks/
├── 📄 README.md
├── 📄 CHANGELOG.md
└── 📄 LICENSE
```

</details>

---

## 📅 Metadata

| Field | Value |
|-------|-------|
| **Version** | 1.0.0 |
| **Last Updated** | 2025-12-29 |
| **Status** | Production Ready |
| **SASMP** | v1.3.0 |
| **Agents** | 7 |
| **Skills** | 7 |
| **Commands** | 4 |

---

## 🤝 Contributing

Contributions are welcome! Please read our [Contributing Guide](CONTRIBUTING.md).

1. Fork the repository
2. Create your feature branch
3. Follow the Golden Format for new skills
4. Submit a pull request

---

## ⚠️ Security

> **Important:** This repository contains third-party code and dependencies.
>
> - ✅ Always review code before using in production
> - ✅ Check dependencies for known vulnerabilities
> - ✅ Follow security best practices
> - ✅ Report security issues privately via [Issues](../../issues)

---

## 📝 License

Copyright © 2025 **Dr. Umit Kacar** & **Muhsin Elcicek**

Custom License - See [LICENSE](LICENSE) for details.

---

## 👥 Contributors

<table>
<tr>
<td align="center">
<strong>Dr. Umit Kacar</strong><br/>
Senior AI Researcher & Engineer
</td>
<td align="center">
<strong>Muhsin Elcicek</strong><br/>
Senior Software Architect
</td>
</tr>
</table>

---

<div align="center">

**Made with ❤️ for the Claude Code Community**

[![GitHub](https://img.shields.io/badge/GitHub-pluginagentmarketplace-black?style=for-the-badge&logo=github)](https://github.com/pluginagentmarketplace)

</div>
