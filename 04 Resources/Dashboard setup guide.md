# ⚙️ Dashboard setup guide

[[04 Resources/Home|← Home]]

## Recommended installed plugins
Your vault already enables **Homepage**, **Tasks**, **Dataview**, **QuickAdd**, **Calendar**, **Day Planner**, **Omnisearch** and **Spaced Repetition**. No new plugin is required for this starter dashboard.

1. In **Settings → Community plugins → Homepage**, set the homepage file to `04 Resources/Home.md`, open on startup, and use Reading view (or Live Preview).
2. In **Settings → Core plugins**, keep **Graph view**, **Backlinks**, **Templates**, **Daily notes** and **Canvas** enabled.
3. In **Settings → Daily notes**, set the template to `05 Templates/Daily Template.md`. Your existing daily note date format is `YYYY/MM/DD`.
4. In **QuickAdd**, use the existing **Quick Task** capture and **New Lecture** choices. A task in `00 Inbox/Task Inbox.md` needs a date like `📅 2026-11-06` to enter due-date panels.
5. Assign a hotkey to **QuickAdd: Run QuickAdd** and **Homepage: Open homepage**. Consider pinning Calendar and Local graph in the sidebar.
6. Use **Graph view** for the whole vault, **Local graph** around a concept, and **Canvas** for curated visual relationships.

## Knowledge workflow
**Capture → Clarify → Connect → Recall → Review**

- Capture handwritten material in a module note, then add a concise searchable text summary.
- Link related notes using `[[wiki links]]` and put deeper concepts in separate notes created with `05 Templates/Concept Template.md`.
- Write actionable items as `- [ ] Your task 📅 YYYY-MM-DD`.
- Use `#flashcards` and `Question::Answer` to create Spaced Repetition cards.
- Use the Weekly Review to process tasks and select what to study next.

## Sync safety
The repository contains **Syncthing** and **GitHub Sync** configurations, and historical sync-conflict files. Keep only one device writing settings at a time and keep a backup. Don't place access tokens or private student information in a public repository. This change avoids plugin configs and handwritten assets.

## Troubleshooting
- **Empty due-date lists:** create checkbox tasks with `📅 YYYY-MM-DD`.
- **Empty assignments table:** add assignment notes in `02 Assignments` using the template.
- **Blank Dataview results:** verify Dataview is enabled and view in Reading/Live Preview.
- **Unhelpful graph:** add explicit internal links between concept notes; SVG-only content won't create semantic links by itself.
