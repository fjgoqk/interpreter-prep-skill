# Interpreter Prep Skill

A reusable skill for Chinese-English interpreting preparation. It guides research, bilingual terminology extraction, source tracking, and preparation-note creation in an Obsidian vault.

## Install

1. Download this repository or the ZIP archive.
2. For DSH, copy the interpreter-prep folder to <vault>/.dsh/skills/interpreter-prep/ when the Obsidian vault is the DSH project root. For Codex, use ~/.codex/skills/interpreter-prep/ (or $CODEX_HOME/skills/interpreter-prep/ if configured).
3. Start a new DSH session or refresh the agent so it discovers the skill.
4. In DSH, make sure the Obsidian vault is the project working directory and the current permission mode allows writing to it. Confirm that web lookup tools are configured if you expect external research.

## Use

In DSH, invoke /interpreter-prep (or ask in natural language); in Codex, invoke $interpreter-prep. For example:

> Prepare for my English-Chinese interpretation assignment on semiconductor supply-chain compliance on 2026-12-03. Audience: government and industry representatives. Use the attached agenda and save the briefing and bilingual glossary in my Obsidian interpretation-prep folder.

The skill defaults to Chinese ↔ English and asks for missing details only when they materially change the preparation. It treats translations as candidates to verify, retains sources, and avoids overwriting existing notes.

## Requirements and limits

The skill supplies reusable instructions; it does not itself provide web search, paid terminology databases, Obsidian access, or DSH installation. Those capabilities must already be available to the agent. If vault writing or external lookup is unavailable, the agent should return a Markdown draft and disclose the limitation.
