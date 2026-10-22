# Ebook Metadata

A Codex skill for editing ebook metadata and covers in EPUB files.

## What it does

- Inspects the current metadata before making changes.
- Uses the book file’s clues to research missing details and match the correct edition.
- Requires confirmation of proposed metadata or cover changes before editing.
- Saves an edited copy separately and verifies embedded EPUB metadata.
- Preserves existing covers and DRM; it does not bypass DRM.

## Files

- [SKILL.md](SKILL.md) — skill instructions and workflow.
- [references/metadata.md](references/metadata.md) — metadata and cover guidance.
- [agents/openai.yaml](agents/openai.yaml) — skill display name and description.

## Install

Copy this folder into your Codex skills directory, for example:

```text
~/.codex/skills/ebook-metadata/
```

Then start a new conversation and ask Codex to edit an ebook’s metadata or cover.