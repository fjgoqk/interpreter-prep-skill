---
name: interpreter-prep
description: Prepare Chinese-English interpreting assignments by researching the subject, extracting terminology, and producing source-traceable bilingual briefing notes for Obsidian.
---

# Interpreter Preparation

Use this skill when preparing for a meeting, conference, interview, site visit, or other interpreting assignment. The default working pair is Chinese ↔ English. Write the briefing narrative, headings, explanations, and interpreting cues in English by default, while keeping the terminology glossary bilingual. Follow any direction, register, or terminology preferences supplied by the user.

## Workflow

1. Identify the assignment date, subject, setting, audience, language direction, and any materials supplied. If an omitted detail materially affects terminology or register, ask a concise question; otherwise proceed and mark assumptions.
2. Read the supplied materials first. Extract likely terms, names, acronyms, figures, organizations, and recurring phrases. Do not invent facts to fill gaps.
3. Research relevant background and terminology using available search or reference tools. Prefer primary sources (official organizations, standards, legislation, speaker/organization materials) and established domain references. If external lookup is unavailable, say so and distinguish user-provided facts from unverified suggestions.
4. For each important term, provide a context-appropriate English and Chinese equivalent, concise definition, context/example or interpreting cue, and a source link when researched. Preserve alternative translations where context changes the choice. Mark uncertain items as Needs verification; never present a guessed translation as confirmed.
5. Prepare a concise briefing with the topic, context, key entities, likely themes, figures/names to verify, and practical interpreting notes (register, abbreviations, pronunciation cues only when verified, and likely ambiguity).
6. Search the Obsidian vault for the configured destination and possible existing notes before writing. Prefer a new dated note in the user's established folder/template. Do not overwrite or rename existing notes. If the destination is unclear or write access is unavailable, present the Markdown for review and explain that it was not saved.
7. Before finishing, check terminology consistency, source links, names, numbers, and duplicate entries. Report the saved path and list any items that still need human confirmation.

## Note format

Use the user's existing Obsidian template when available. Otherwise use this structure:

~~~markdown
---
type: interpreting-prep
date: YYYY-MM-DD
languages: [Chinese, English]
subject: "..."
status: draft
---

# [Subject] — Interpreting Preparation

## Assignment brief
- Date / setting:
- Language direction:
- Audience and register:
- Source materials:

## Background
[Short, source-linked summary relevant to the assignment.]

## Bilingual terminology
| Chinese term | English term | Definition / context | Interpreting cue or example | Source | Status |
|---|---|---|---|---|---|

## Names, figures, and acronyms to verify
| Item | Preferred rendering / value | Evidence | Status |
|---|---|---|---|

## Useful phrases
| Chinese expression | Natural English rendering | Context / register |
|---|---|---|

## Open questions
- [Unresolved item and what would verify it.]

## Sources
- [Title](URL) — source type and access date
~~~

Keep the note practical for live interpreting: prioritize likely-to-be-used terms and compact cues over a broad encyclopedia entry. Use the actual assignment date for the filename when known, for example YYYY-MM-DD - Subject - Interpreting Prep.md. Do not put confidential source text into an external search query unless the user has authorized that use.
