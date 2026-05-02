---
date: 2026-05-02
type: policy
project: null
---

# Repository naming policy

IATF organization repositories follow a small, stable set of naming
rules. The goal is clean, human-readable URLs for project repos, with
auditable numbering kept where it actually helps — in governance
records, not in repository names.

## Rules

- **Public accepted projects:** `iatf-<project-slug>`. Descriptive, no
  numbering. Stable URLs matter more than chronology, and GitHub
  already records creation date, issues, and releases.
- **Private raw intake:** `iatf-intake`. Holds raw form submissions
  before redaction.
- **Public records (numbered):**
  - `iatf-governance/requests/YYYY-NNN-<slug>.md`
  - `iatf-governance/decisions/YYYY-NNN-<slug>.md`
  Numbering belongs in governance records, not in repository names.
- **Legacy archived repositories:** `archived-iatf-<slug>`.

## Why no numbering in repo names

1. Stable human-readable URLs matter more than sequence.
2. Numbers create maintenance friction when a request is withdrawn,
   merged, renamed, or split.
3. GitHub already provides chronology through creation date, issues,
   releases, and registry entries.
4. IATF is not an RFC series; the public-facing artifact is software,
   not a numbered specification.

## End-to-end flow

```
Raw form submission
  → private issue in iatf-intake
  → public redacted record: iatf-governance/requests/YYYY-NNN-<slug>.md
  → accepted project repo: iatf-<project-slug>
  → governance decision: iatf-governance/decisions/YYYY-NNN-<slug>.md
```

## Examples

```
iatf-plain-language-reader
iatf-accessible-map
iatf-screen-reader-test-kit

archived-iatf-selfie
archived-iatf-bot

iatf-governance/requests/2026-001-plain-language-reader.md
iatf-governance/decisions/2026-001-repository-naming-policy.md
```
