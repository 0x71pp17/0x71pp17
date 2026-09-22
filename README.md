Security research across AI-integrated and agentic systems, web applications, distributed systems,
and secure-by-design code.

---

## 💻 Tech Stack

Everything below is used in the repositories on this profile.

**Languages**

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Go](https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)
![Solidity](https://img.shields.io/badge/Solidity-%23363636.svg?style=for-the-badge&logo=solidity&logoColor=white)
![Move](https://img.shields.io/badge/Move-%234A90D9.svg?style=for-the-badge&logoColor=white)
![Shell Script](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=for-the-badge&logo=markdown&logoColor=white)

**AI & retrieval**

![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-%23FF6F61.svg?style=for-the-badge&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-%23000000.svg?style=for-the-badge&logo=ollama&logoColor=white)
![Anthropic API](https://img.shields.io/badge/Anthropic_API-%23D4A27F.svg?style=for-the-badge&logo=anthropic&logoColor=white)

**Testing & tooling**

![pytest](https://img.shields.io/badge/pytest-%230A9EDC.svg?style=for-the-badge&logo=pytest&logoColor=white)
![Foundry](https://img.shields.io/badge/Foundry-%23000000.svg?style=for-the-badge&logoColor=white)
![Burp Suite](https://img.shields.io/badge/Burp_Suite-%23FF6633.svg?style=for-the-badge&logoColor=white)
![Aptos CLI](https://img.shields.io/badge/Aptos_CLI-%23000000.svg?style=for-the-badge&logoColor=white)
![GNU Make](https://img.shields.io/badge/GNU_Make-%23427819.svg?style=for-the-badge&logo=gnu&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)
![golangci-lint](https://img.shields.io/badge/golangci--lint-%23F7DF1E.svg?style=for-the-badge&logoColor=black)
![gosec](https://img.shields.io/badge/gosec-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white)

---

## 🔍 Focus areas

**AI & agentic systems** — retrieval authorization and tenant isolation, direct and indirect prompt
injection, guardrail evasion, agent memory persistence, and exfiltration through sanctioned
channels.

**Application & API security** — exploit-chain reasoning across web application and API attack
surface, walked through so the attack can be reconstructed from first principles.

**Distributed systems** — protocol-layer and on-chain work: defensive build patterns for the EVM,
each tied to the EIP and the failure mode it exists to prevent, and offensive work against financial
state machines through worked solutions.

**Runtime and VM layer** what a platform structurally enforces versus what it leaves to the
developer, and differential testing across runtimes to find where two of them do observably
different things with the same program.

---

## 📂 What's here

**[agent-action-broker](https://github.com/0x71pp17/agent-action-broker)** Policy decision point for
tool-using agents. Mediates each tool call by capability and information flow, fails closed, and
returns a least-privilege downgrade on denial. Carries an audit trail and an AgentDojo-modeled
evaluation reporting injection-block and utility rates.

**[mcp-controlplane-scan](https://github.com/0x71pp17/mcp-controlplane-scan)** Scanner for the
localhost HTTP control plane exposed by local AI tools and MCP servers. Flags DNS-rebinding,
cross-site, and unauthenticated-read failure classes, and ships a hardened reference server that
passes its own checks.

**[agentic-rag-tenant-lab](https://github.com/0x71pp17/agentic-rag-tenant-lab)** Multi-tenant
agentic RAG security lab. Four retrieval authorization flaws, five defense layers, measured attack
success rates.

**[lab-journal](https://github.com/0x71pp17/lab-journal)** Technical write-ups and notes, with
documented reproducible attack chains and analysis.

**[modern-solidity-patterns](https://github.com/0x71pp17/modern-solidity-patterns)** Defensive
build reference for Solidity 0.8.x and the current EVM. The patterns, each stating the failure mode
it prevents, grounded in the relevant EIPs and audited libraries.

**[move-security-patterns](https://github.com/0x71pp17/move-security-patterns)** A defensive
reference for building on Aptos Move, stating which layer of the platform covers each failure mode
and how far that coverage reaches. Every pattern carries an adversarial test that tries the attack.

**[runtime-differential](https://github.com/0x71pp17/runtime-differential)** Runs the same operation
on more than one blockchain runtime and reports what each one did. It records no expectations, so a
runtime changing behaviour changes the reading rather than failing against a recorded belief.
