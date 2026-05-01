# Public request summaries

Redacted, published summaries of accessibility requests that came into
IATF and were reviewed.

## Relationship to `iatf-requests`

- **`iatf-requests` (private):** raw intake from the website form,
  email, or Discord. May contain personal contact details, sensitive
  context, spam, or harmful content. Only IATF maintainers can read it.
- **`iatf-governance/requests/` (public, this folder):** filtered and
  redacted summaries of requests that have been accepted, declined,
  deferred, or reshaped. These are what the public registry and
  transparency page can link to.

A request is **never** published verbatim. Summaries remove personal
contact details, private addresses, and identifying information about
individual users of assistive technologies before publication.

## What gets published

- Accepted requests, once the project repository exists.
- Declined or deferred requests, when there is public value in
  recording the reasoning (e.g. recurring out-of-scope themes).
- Requests that were reshaped before acceptance, with a short note on
  what changed.

Spam, hostile messages, and clearly off-topic submissions are filtered
out at the private intake stage and are not summarized here.

## File naming

`YYYY-MM-DD-<slug>.md`, ordered by the date the request was reviewed.

## Minimal entry shape

```markdown
---
date: 2026-05-02
status: accepted | declined | deferred | reshaped
project: iatf-<name>      # if accepted
---

## Need

Short, plain-language description of the accessibility need.

## Outcome

What IATF decided and why.
```

## Editorial policy

The full editorial policy is at <https://iatf.cc/governance/> under
"Public request records".
