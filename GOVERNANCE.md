# Janus Governance Organization Governance

## Purpose and scope

Janus Governance develops public governance architecture for AI-assisted technical work. This document establishes organization-wide defaults for public repositories. The Janus Governance Core is the canonical source for normative definitions; this document does not amend or add requirements to the Core.

## Human authority and roles

The Head is the final human authority for the organization. The Head approves scope, resolves material ambiguity, and makes final decisions about normative change, publication, deployment, and acceptance.

The architect or engineer translates human intent into an explicit scope, sequence, boundaries, evidence requirements, and decision gates. Implementers and maintainers operate only within the authorized scope and preserve the evidence needed for review.

Codex, Claude, Copilot, and other automated agents are tools with assigned roles. They do not possess human authority, authorize changes, act as human co-authors, or replace the Head's final decision. Their output remains subject to human direction and review.

## Change classes

- **Informational changes** clarify or describe without changing system behavior or normative meaning.
- **Implementation changes** alter code, automation, configuration, or other executable behavior within established requirements.
- **Normative changes** alter governing definitions, requirements, authority, or decision rules and must be directed to the canonical Core when they affect Core semantics.
- **Publication or deployment** makes an approved result externally available or operational. It is a separate decision from implementation.

Classification determines the appropriate authorization, evidence, and review gate. Tests and successful builds are implementation evidence; by themselves, they do not demonstrate semantic conformity with governing requirements.

## Change process and evidence

Changes to `main` use a dedicated branch, a pull request, human review, and a merge commit unless an explicitly authorized repository rule provides otherwise. Evidence before and after a change must be proportional to its risk and sufficient to establish the baseline, authorized delta, and resulting state.

Contributors must preserve traceability, provenance, and historical versions. Changes should be minimal and reversible, and review records should distinguish observed facts, inferences, and unverified points.

## Repository boundaries

Public repositories contain material approved for public use. Private Operations and private Labs repositories have distinct purposes and access boundaries. Sensitive data, operational material, private research, credentials, personal information, and private Labs assets must not be moved into public repositories without specific human authorization.
