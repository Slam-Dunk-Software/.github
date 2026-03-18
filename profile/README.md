# Slam Dunk Software

We build the **Extremely Personal Software** ecosystem. Tools for running your own software, on your own machines, without the cloud tax.

---

### Core toolchain

| | |
|---|---|
| [**epm**](https://github.com/Slam-Dunk-Software/epm) | Package manager. Install, publish, and manage EPS packages. |
| [**epc**](https://github.com/Slam-Dunk-Software/epc) | Process supervisor. Deploy packages as persistent local services. |
| [**eps_mcp**](https://github.com/Slam-Dunk-Software/eps_mcp) | MCP server. Gives Claude authoritative knowledge of the EPS ecosystem. |
| [**eps_skills**](https://github.com/Slam-Dunk-Software/eps_skills) | Slash commands for Claude Code — semver bumps, releases, and more. |
| [**eps_docs**](https://github.com/Slam-Dunk-Software/eps_docs) | ADRs, concepts, and guides for the EPS ecosystem. |

---

### Harnesses

Ready-to-deploy services you can install with `epm new <name>` and make your own.

| | |
|---|---|
| [**todo**](https://github.com/Slam-Dunk-Software/todo) | Minimal task manager — add, complete, delete, list. |
| [**notes**](https://github.com/Slam-Dunk-Software/notes) | Minimal notes app — create, edit, search. |
| [**crm**](https://github.com/Slam-Dunk-Software/crm) | Personal CRM — contacts, interactions, follow-ups. |
| [**daily-brief**](https://github.com/Slam-Dunk-Software/daily-brief) | Texts you a summary of open tasks every morning. |
| [**txtme**](https://github.com/Slam-Dunk-Software/txtme) | SMS notification endpoint — POST here to send yourself a text. |
| [**webterm**](https://github.com/Slam-Dunk-Software/webterm) | Web terminal with command palette — access your machine from any browser. |
| [**observatory**](https://github.com/Slam-Dunk-Software/observatory) | Health monitoring dashboard — watches your EPC services. |

---

### Utilities

| | |
|---|---|
| [**eps_seasonings**](https://github.com/Slam-Dunk-Software/eps_seasonings) | Small add-ons that extend EPS harnesses. |
| [**tree_walker**](https://github.com/Slam-Dunk-Software/tree_walker) | Codebase index — extracts public symbols across your projects. |

---

> **EPS** is a philosophy as much as a stack: own your tools, run them yourself, vibe-upgrade them into exactly what you need.
> Get started → `curl -fsSL https://raw.githubusercontent.com/Slam-Dunk-Software/epm/main/install.sh | sh`
