# Janus Governance

A governance architecture for AI-assisted development systems.

---

## What is Janus

Janus is a protocol-driven governance architecture for systems where humans
and AI collaborate in technical production. It enforces traceability,
deterministic reconstruction, and explicit human authority — at the
operational level where development decisions actually happen.

---

## Start Here

- [janusgovernance.org](https://janusgovernance.org) — start here
- [Architecture](https://janusgovernance.org/docs/architecture/) — design and system model
- [Foundational Paper](https://janusgovernance.org/paper/janus-foundational-paper-v1.0.pdf) — formal specification

---

## Project Structure

Core → Framework → Runtime → Docs

| Repository | Purpose |
|---|---|
| [janus-governance-core](https://github.com/Janus-Governance/janus-governance-core) | Conceptual kernel, RFCs, foundational paper, and canonical governance definitions |
| [janus-framework-stack](https://github.com/Janus-Governance/janus-framework-stack) | Operational protocol stack for framework-level governance |
| [janus-runtime](https://github.com/Janus-Governance/janus-runtime) | Reference runtime implementations of the Janus governance model |
| [janus-rfc](https://github.com/Janus-Governance/janus-rfc) | Formal protocol specifications (RFC series) |
| [janus-docs](https://github.com/Janus-Governance/janus-docs) | Extended documentation, architecture guides, and usage references |
| [janus-governance.github.io](https://github.com/Janus-Governance/janus-governance.github.io) | Public website source |

---

## Why Janus

- AI-assisted development introduces **diffuse authority** — it is often unclear who decided what, and why
- Traditional frameworks do not govern the **micro-operational layer** where human and AI collaboration actually occurs
- Missing actions are as significant as incorrect ones — Janus makes **omissions first-class governance signals** (E−)
- Governance state must be **deterministically reconstructible** from append-only logs — not inferred from memory or documentation
- Compliance frameworks define what is required — Janus provides the **operational layer** that makes it verifiable

---

## Principle

A system is trustworthy when every decision, omission, and human authority event
is recorded, traceable, and reconstructible — not assumed.
