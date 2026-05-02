# iatf-governance

Durable public records for IATF.

This repository is the long-lived public record for the
[International Accessibility Task Force](https://iatf.cc). It holds the
content that the website's
[`/governance/`](https://iatf.cc/governance/) and
[`/transparency/`](https://iatf.cc/transparency/) pages summarize, and that
project repositories link back to.

## What lives here

| Folder | Contents |
| ------ | -------- |
| `chair/` | Chair role records: terms, election announcements, results. |
| `decisions/` | Acceptance, archival, and reassignment decisions for IATF projects. |
| `costs/` | Operating cost records, by year. |
| `requests/` | Published, redacted summaries of accessibility requests. |

Each folder has its own `README.md` describing the format used for entries
in that area.

## What does **not** live here

- **Raw intake from the website form.** Those go to the private
  `iatf-intake` repository. Records here are summaries that have been
  filtered, redacted, and approved for publication.
- **Project source code.** Each accepted project lives in its own
  `iatf-<project-slug>` repository.
- **Live discussion.** Conversations happen on Discord and in repo
  issues. Decisions that affect a project or governance are summarized
  into this repository when they are made.

## Editorial policy

- Plain English source. Translations may be added later.
- Entries are append-mostly. Corrections are made by adding a new entry
  that supersedes the old one, not by silently rewriting history.
- Personal contact details, private addresses, and identifying
  information about individual users of assistive technologies are
  removed before anything is published here.
- Records are excluded from search engine indexing where technically
  practical.

The full editorial policy is on
[`/governance/`](https://iatf.cc/governance/) under "Public request
records".

## Contributing

Most entries are added by the IATF chair or a maintainer with
organization-level access. If you have a correction or want to flag
something missing, open an issue or email <contact@iatf.cc>.

See the org-wide
[CONTRIBUTING](https://github.com/international-accessibility-task-force/.github/blob/main/CONTRIBUTING.md)
and [Code of Conduct](https://github.com/international-accessibility-task-force/.github/blob/main/CODE_OF_CONDUCT.md).

## Contact

- Email: <contact@iatf.cc>
- Discord: <https://iatf.cc/discord>

## License

Content is licensed under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/).
