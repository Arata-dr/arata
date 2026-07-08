# Research Output Fact-Check Rules

Last updated: 2026-07-08

## Purpose

Use these rules when drafting, reviewing, or polishing:

- research-conference slides
- grant and KAKEN materials
- collaborator-facing summaries
- clinical-needs lab materials
- device-collaboration explanations
- education or seminar reports
- email-ready progress summaries

## Source Hierarchy

Prefer evidence in this order:

1. Official pages, official application guidelines, official forms, official manufacturer or society pages.
2. Directly inspected email, calendar, Drive/Docs, GitHub, or local files in the current run.
3. Local project notes and prior AI output as secondary context only.
4. Search-result snippets only as leads. Open the actual source before treating a claim as checked.

Never imply a source was checked if it was not checked in the current run.

## Evidence Strength

| Evidence seen directly | Allowed status | Do not say |
|---|---|---|
| Official receipt email, completion screen, auto-reply, or sent application email | `受付完了`, `提出済み`, `送信完了`, `確認済み` | Do not weaken unless conflicting evidence exists |
| Final PDF, input copy, recommendation approval, but no receipt | `提出対応済み`, `提出準備済み`, `受付証跡要確認` | `受付完了`, `提出済み確定` |
| Candidate list, spreadsheet, old AI output | `候補`, `要確認` | `提出済み`, `完了`, `確定` |
| Gmail draft | `下書き作成済み/送信未実施` | `送付済み`, `共有済み`, `提出済み` |
| Drive filename only | `Drive上にファイル名を確認`, `本文未確認` | `内容確認済み`, `共有済み` |
| Calendar event inspected | `Calendar確認済み` | `Gmailのみ確認済み` |
| GitHub repository accessible but no relevant commit/issue/PR | `アクセス可能repoあり、反映未実施` | `GitHub反映済み` |
| Local file inspected | `ローカルファイルで確認` | `Driveでも確認済み` |

## Research Expression Gates

- Keep the primary endpoint singular unless a verified protocol says otherwise.
- Exploratory devices and measurements must not take over the main research story.
- For BreScan, SPLYZA Motion, SKINOS, dynamic X-ray, sweat/sudomotor measures, and respiration-device collaboration, use `探索的`, `副次`, `feasibility`, or `教育応用候補`.
- Do not write `確立された評価指標`, `証明する`, or `明らかである` for unverified exploratory measures.
- For COA/PRO instruments, do not write `使用可` until permission, official version, Japanese version, and print/distribution conditions are checked.

## Slide And Report Rules

- A research conference is a progress report. Show completed actions, counts, deadlines, and next artifacts.
- Use formal event names and themes when available. Do not rely only on a short internal nickname.
- Use concrete activity names before abstract interpretations.
- Put source-system labels such as Gmail, Drive, Calendar, or local file paths in notes or QC memos, not visible audience-facing slide bodies, unless the slide is explicitly an evidence table.
- Separate `反映済み`, `下書き`, `提出対応済み`, `受付完了`, and `要確認`.

## Final Answer Gate

Before returning a final answer, internally check:

1. Does it answer the user's objective?
2. Are all constraints followed?
3. Are missing, contradictory, ambiguous, or overconfident claims removed?
4. Is the logic natural and readable?
5. Are examples, steps, dates, or decision criteria concrete enough?
6. Is it concise enough for practical use?
7. Are unstable facts verified or marked `要確認`?
8. Could the user use the output as-is?

Do not output the internal review notes.
