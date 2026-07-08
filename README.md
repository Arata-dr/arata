# Clinical Research AI Rules

Last updated: 2026-07-08

This repository stores portable rules for using Codex, ChatGPT, and similar AI tools in Japanese clinical-research operations.

It is intentionally public-safe:

- no patient information
- no personal email bodies
- no unpublished research data
- no API keys, tokens, or account details
- no raw connector exports

Project-specific names, private correspondence, submission receipts, and internal file paths should be kept in a private note or local OS/Skill file, then pasted only when the working context requires them.

## How To Use

For ChatGPT:

1. Open `chatgpt/START_PROMPT.md`.
2. Paste it at the beginning of the chat or place it in a ChatGPT Project instruction.
3. Add the private context for the current task separately, using `templates/PRIVATE_CONTEXT_TEMPLATE.md`.
4. Ask ChatGPT to cite which source it actually inspected before it labels anything as confirmed.

For Codex:

1. Keep local Skill files as the execution layer.
2. Use this repository as the portable rulebook and audit checklist.
3. Do not treat this public repository as a substitute for private evidence files or source inspection.

## File Map

| Path | Purpose |
|---|---|
| `chatgpt/START_PROMPT.md` | Paste-ready prompt for ChatGPT or a ChatGPT Project. |
| `rules/research-output-factcheck.md` | Evidence labels, source hierarchy, research-expression gates, and external-source rules. |
| `rules/grant-deadline-and-email-evidence.md` | Grant deadline triage and email-evidence handling. |
| `checklists/research-conference-slide-qc.md` | Research-conference slide QC checklist, including formal event names and numeric achievements. |
| `templates/PRIVATE_CONTEXT_TEMPLATE.md` | Template for private task-specific details that should not be committed to a public repo. |
| `CHANGELOG.md` | Change history. |

## Core Rule

Do not upgrade weak evidence into strong status.

Examples:

- A Gmail draft is not a sent email.
- A local PDF is not a submitted application.
- A Drive filename is not content confirmation.
- A GitHub-accessible repository is not a completed GitHub reflection.
- A search result snippet is not an official source.

When evidence is incomplete, write `要確認` and state what would prove the claim.
