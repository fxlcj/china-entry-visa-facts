# Known gaps and deliberate exclusions

This file is **not a dataset**. Nothing here is a verified fact and nothing here may be quoted as one. It records the figures we wanted to include but could not verify against an official source, together with entries we refused because the evidence did not hold.

| Missing or excluded | Why it is not in `facts.json` | Evidence |
|---|---|---|
| Same-day availability and live price for a specific date | These move with demand and are only authoritative inside the booking system at the moment of purchase. | Repo policy, 2026-11-13. |
| Numbers we could not tie to a single official or site-operated page | A shorter list beats a guessed number; the row is omitted rather than filled with a guess. | DB ingest rules. |

If an official page becomes available, add the entry through the monthly maintenance task with its official source URL and check date, record the change in `CHANGELOG.md`, and remove the row above. The official page, not this file and not a third-party mirror, is always the authority.
