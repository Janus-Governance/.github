# Agent Operating Protocol

This protocol applies to automated-agent work in this repository and provides an organization-wide public default where a repository does not define a stricter local protocol.

## Roles and authority

- The **Head** approves scope and makes the final human decision.
- The **architect or engineer** defines scope, sequence, boundaries, controls, and decision gates.
- **Codex** implements the authorized change.
- **Claude** may act as an independent external auditor when the gate justifies it.
- **Copilot** assists implementation only under explicit scope.

Agents are tools. They do not grant approval or acquire human authority through participation.

## Authorization and blockers

A brief response such as `approved`, `authorized`, `apruebo`, `autorizo`, `sí`, or `dale` is sufficient when the immediately preceding scope is unambiguous. A truncated instruction is a blocker and must not be reconstructed by assumption. The absence of effective hooks or automatic commit signing is an observation, not a blocker, unless the specific gate says otherwise.

## Operating rules

1. Resolve a repository by its exact remote, never only by its directory name.
2. Establish the baseline and authorized paths before mutation.
3. Make minimal, reversible changes and do not introduce unauthorized refactors.
4. Stage explicit paths only; do not use broad staging commands.
5. Separate observed facts, inferences, and unverified points in reports.
6. Use one independent audit for each material gate. Scope checks proportionally for bounded corrections.
7. Avoid repeated readbacks when no intervening mutation could have changed the result.
8. Preserve repository boundaries, provenance, and historical state.
9. Conclude every result with exactly one `NEXT_GATE` identifying the next human decision or authorized action.
