# Company UI/UX standards (shared)

This folder is the **shared UI/UX guideline library** for all projects. It is written as Markdown so it works in **GitHub, Figma workflows, Claude (Design & Code), and Google Stitch**—see `DESIGN.md` and `AGENTS.md` for tool-oriented entry points.

## Canonical entry (start here)

Open the hub:

[`UI UX Guidelines/UI UX guidelines 20be6c5f913d4f53ac0e76eb5e904eef.md`](UI%20UX%20Guidelines/UI%20UX%20guidelines%2020be6c5f913d4f53ac0e76eb5e904eef.md)

New readers should also use:

[`UI UX Guidelines/Planning & Meetings/Company UI UX standards/Onboarding — start here 3454544eeb428192b340d7326b5015d4.md`](UI%20UX%20Guidelines/Planning%20%26%20Meetings/Company%20UI%20UX%20standards/Onboarding%20%E2%80%94%20start%20here%203454544eeb428192b340d7326b5015d4.md)

## Folder map

| Path | Purpose |
| --- | --- |
| `UI UX Guidelines/` | Full hub: standards chapters, process, workflow, pilots |
| `UI UX Guidelines/Standards/` | Numbered chapters (scope, tokens, components, brand) |
| `UI UX Guidelines/Workflow & Tooling/` | Figma · Notion · Repo · Stitch consolidation, Claude loop |
| `UI UX Guidelines/Projects/` | Pilot outputs, prototypes, project notes |
| `DESIGN.md` (repo root) | Compressed rules for **Stitch / agents**—refresh when tokens change |
| `AGENTS.md` | Pointers for **Claude, Cursor, and other AI tools** |

## Using this in an application repo

- **Human spec:** link or copy sections into `docs/design/` as needed; keep the **hub** as the narrative source of truth.
- **Engineering:** mirror token names in `globals.css` (or your theme) to match **Brand & tokens** and **Components** chapters.
- **Figma:** library variables and component names should match token names referenced in the hub.
- **Claude Design / Claude Code:** follow `AGENTS.md` and the workflow chapter under `UI UX Guidelines/Workflow & Tooling/`.
- **Google Stitch:** import or sync from root `DESIGN.md`; regenerate when the semantic palette or guardrails change.

## Sync rhythm (short)

When **CSS variables or Tailwind tokens** change: update code first, then the hub tables, then `DESIGN.md`. See [`Workflow & Tooling/9 · Consolidation map — Notion · Repo · Stitch · Figma`](UI%20UX%20Guidelines/Workflow%20%26%20Tooling/9%20%C2%B7%20Consolidation%20map%20%E2%80%94%20Notion%20%C2%B7%20Repo%20%C2%B7%20Stitch%20%C2%B7%20F%2034a4544eeb4281b5a45bd1d1321b52bf.md).

## GitHub notes

- Paths contain spaces and special characters; GitHub renders Markdown links when URL-encoded as in this README.
- Clone on any OS; `.gitattributes` keeps line endings reasonable for editors and diffs.
