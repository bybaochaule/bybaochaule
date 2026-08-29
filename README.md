# Hi, I'm Bao Chau 👋

I build open-source tools and Agent Skills for making AI agents more reliable, testable, safe, and useful in real workflows.

My current focus is the infrastructure around AI agents:

**evaluation → verification → tool use → workflow reliability → reusable skills**

## What I'm building

### 🧪 Agent evaluation

I’m exploring reproducible ways to answer a simple question:

> **Does adding an Agent Skill actually make the agent better?**

The goal is to move skill development away from “this prompt looks good” toward measurable behavior, reproducible tests, failure analysis, and evidence.

### 🛠 Agent workflows

I build reusable Agent Skills that turn complex work into explicit processes with:

* clear triggering conditions
* decision logic
* tool boundaries
* validation gates
* failure handling
* observable quality checks

### 🔐 Safe tool use

I’m interested in how agents can use APIs, connectors, MCP servers, files, and external services while preserving least privilege, user authorization, traceability, and safe failure behavior.

## Selected work

### Testing, Debugging & Optimization

An Agent Skill for designing evaluation scenarios, measuring baselines, classifying failures, tracking accuracy and latency, and running regression tests on agent systems.

### Tools & Integrations Knowledge

A workflow for planning and validating agent integrations while separating planning from execution and requiring authorization for consequential actions.

### PDF Allrounder

A document workflow skill covering PDF reading, conversion, OCR, editing, rendering, and visual quality verification.

## Current project

### SkillAblate

**A vendor-neutral ablation protocol for measuring what an Agent Skill actually changes.**

The experiment is simple:

```text
same task
same model
same tools
same environment
same budget

WITHOUT SKILL
      vs
WITH SKILL

      ↓

measured outcome
```

The project will focus on reproducible evidence rather than subjective “quality scores.”

Planned areas include:

```text
benchmark specification
deterministic graders
run manifests
skill fingerprints
raw evidence
baseline-vs-skill comparisons
cross-agent interoperability
regression testing
CI integration
```

The long-term goal is to help developers answer:

**Did the skill improve the agent, harm it, or make no measurable difference?**

## Open-source principles

I want the projects here to be:

**Useful** — solve real agent-development problems.

**Testable** — important claims should have evidence.

**Portable** — avoid unnecessary dependence on one model provider.

**Transparent** — publish limitations and negative results.

**Safe** — permissions and consequential actions should be explicit.

**Collaborative** — outside issues, experiments, critiques, and pull requests are welcome.

## Sponsors

I maintain these projects independently.

Sponsorship helps fund:

* model/API costs for reproducible experiments
* cross-model testing
* benchmark infrastructure
* documentation
* maintenance
* security and reliability work

Funding does **not** buy favorable benchmark results or influence technical conclusions.

If your team works on AI agents, Agent Skills, MCP, evaluations, developer tooling, or agent security, I’d be glad to collaborate through issues and pull requests.

## Current direction

I’m especially interested in contributions and research around:

`Agent Skills` · `AI agents` · `agent evals` · `MCP` · `Codex` · `Claude` · `Gemini` · `agent reliability` · `agent security` · `open-source AI tooling`

---

If something here saves you time or improves your agent workflow, a ⭐, issue, test case, contribution, or sponsorship all help move the work forward.
