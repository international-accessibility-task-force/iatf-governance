# Decisions

Acceptance, archival, and reassignment decisions for IATF projects.

The day-to-day source of truth for a project is its own repository.
Records here exist so that organization-level decisions remain readable
even if a project's repository is later renamed, archived, or moved.

## What goes here

- Project acceptance: the public announcement that a request became an
  IATF project.
- Project archival: when a project stops being actively maintained.
- Reassignment: when a maintainer steps away and someone else takes over.
- Other organization-level decisions that affect more than one repo.

## What does **not** go here

- Per-project technical decisions. Those live in the project repository.
- Live discussion. Decisions are summarized here once made.

## File naming

`YYYY-MM-DD-<slug>.md`, ordered by decision date.

## Minimal entry shape

```markdown
---
date: 2026-05-02
type: acceptance | archival | reassignment | other
project: iatf-<name>
---

Short description of what was decided and why.
```
