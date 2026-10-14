# USS Nimitz Fury — Keeper Repo

One repo, one project. Each deck is a top-level folder; imported repos live at `<deck>/<repo-name>/` with full history (git subtree).

| Deck | Contents |
|---|---|
| `bridge/` | Hub, Bridge OS, crew stations (Starship-Poenix-Ascent, pianomanuel.github.io) |
| `comms/` | Sites: revelation-study, pianomanuel (pianomanuel.com) |
| `sickbay/` | Diagnostics, health-of-system checks |
| `engineering/` | Builds, deploy scripts, starship-agent, SQL (archived data) |
| `science/` | Music: Gloria, scores, audio projects |
| `security/` | Backups, audits, CI policies |
| `templates/` | Shared site-builder layouts |
| `docs/` | Documentation pages |

## Naming convention
- Branches: `fury/<ISSUE-KEY>-<slug>` (e.g. `fury/PMC-411-repo-consolidation`)
- Files: `<deck>-<system>-<topic>-YYYY-MM-DD.<ext>`
- Jira titles: `[<DECK>] <summary>`
- Confluence pages: `NIMITZ · <Deck> · <Topic>`
- Folders: lowercase, hyphenated
