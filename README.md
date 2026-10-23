### I build governance tooling for AI agents.

Two products, each one self-hosted Go binary with no dependencies, under Apache-2.0:

- **[Quilzo](https://github.com/Quilzo/Quilzo)** — the control plane for AI agents and the content they produce: every agent gets an identity, a policy, a budget and a signed record, and a person approves the actions that matter · [manual](https://quilzo.github.io/) · [quilzo.io](https://quilzo.io/)
- **[Vaigil](https://github.com/Vaigil/Vaigil)** — open-source AI security operations: SIEM, SOAR and vulnerability management, with an AI analyst that suggests and never decides · [manual](https://vaigil.github.io/)

And five Apache-2.0 packages that work alone and compose into one control plane:

- **[revoco](https://github.com/rsh1k/revoco)** — undo for AI-agent actions: the rollback is planned before the action runs, proven by drills, and a compromised grant's whole blast radius rolls back in one call
- **[retie](https://github.com/rsh1k/retie)** — a terminal coding agent that classifies every action by how hard it is to undo
- **[mcp-gate](https://github.com/rsh1k/mcp-gate)** — a policy firewall for MCP tool calls, with redaction on the wire
- **[veritrail](https://github.com/rsh1k/veritrail)** — tamper-evident provenance: prove who authorized any agent action
- **[mnemosyne](https://github.com/rsh1k/mnemosyne)** — a memory-integrity firewall for agents that remember

Start at **[agent-governance](https://github.com/rsh1k/agent-governance)** — the 60-second tour with measured numbers.
