# Failure Modes

This document defines known catastrophic failure classes.

Design exists to prevent these.

---

## Authority Drift
When tools, agents, or processes gain authority implicitly.

Mitigation:
- Explicit ownership
- Canon separation
- Version locking

---

## Ontology Drift
When meaning changes silently over time.

Mitigation:
- Canon before schema
- Schema before data
- Immutable IDs

---

## Automation Override
When automation executes without human intent.

Mitigation:
- Read-only defaults
- Explicit approval gates
- Logged promotion paths

---

## Metric Gaming
When values are reduced to numbers and optimized incorrectly.

Mitigation:
- Principles, not gamification
- Narrative context
- Human judgment

---

## Memory Loss
When rejected or failed ideas reappear as “new.”

Mitigation:
- Persistent rejection records
- Non-destructive history
