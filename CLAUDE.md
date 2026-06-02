# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## What this repository is

This is a **documentation-only** repository. It contains no source code, build system, or tests. It defines the IC Engineering hiring process for the Bangalore, India in-office team, split across several linked Markdown files. There is nothing to build, lint, or run — work here is editing prose, keeping Markdown well-formed, preserving table structures, **keeping relative inter-file links valid**, and maintaining internal consistency across files (see below).

## File layout

Only **`HiringOverview.md`** (plus this `CLAUDE.md`) lives at the repo root; every other content doc is in a subfolder.

- **`HiringOverview.md`** — the index/entry point at the root: the candidate-type × round matrix, rounds-by-level table, pipeline summary, the level-specific expectations table, the Job Descriptions index, and links to every other doc. Start here.
- **`screening/ResumeScreening.md`** — per-level sourcing criteria (Junior 2–4 YOE, Senior 6–8 YOE, Staff 8–12 YOE, Engineering Manager 8–12 incl. 3+ in leadership).
- **`evaluation/Scorecards.md`** — the six-dimension scorecard, the "Emphasis by round / module" table, required-per-round notes, and the debrief/leveling policy.
- **`JobDescription/*.md`** — portal-ready, candidate-facing job descriptions, one per role, derived from `screening/ResumeScreening.md` and the round files. They are indexed from a "Job Descriptions" table in `HiringOverview.md` (no separate README).
- **`rounds/*.md`** — one file per interview round (`ai-enabled-coding`, `code-walkthrough`, `pr-review-and-code-comprehension`, `system-design-distributed-systems`, `engineering-leadership`, `hm-technical-taste-and-fit`). Each follows the Overview → Format → Evaluation Criteria → Level Calibration shape and back-links to the overview and Scorecards.

Every doc cross-links the others with **relative** paths (`screening/`, `evaluation/`, `rounds/`, `JobDescription/` from the root; `../` to climb out of a subfolder). When renaming or moving a file, update the links in the overview matrix, the expectations table, the Scorecards emphasis table, and any sibling round that references it.

The content is heavily cross-referential. When editing any one part, these invariants must stay consistent across **all** the files that restate them:

- **Three candidate types / pipelines:** External, Internal, and Engineering Manager (EM). EM is a separate **management track**, not part of the Junior/Senior/Staff IC ladder.
- **Round 1 splits by candidate type.** External R1 = AI-enabled coding & problem solving. Internal R1 = the candidate's choice of code walkthrough **or** PR review. EM R1 = PR review. The PR Review module is therefore reused three ways (External R2, Internal R1 option, EM R1) — its single description must stay valid for all uses. Likewise System Design and the HM round are shared by all three pipelines.
- **Round numbering diverges between pipelines.** External = 4 rounds (AI coding → PR review → System Design → HM). Internal = 3 rounds at **every** level (walkthrough/PR-review → System Design → HM). EM = 4 rounds (PR review → System Design → Engineering Leadership → HM). So System Design is External R3 / Internal R2 / EM R2, and HM is External R4 / Internal R3 / EM R4. Prefer **module names** over round numbers when stating cross-cutting rules (e.g. the leveling/veto policy) so they stay unambiguous.
- **Engineering Leadership** is the only EM-exclusive module (EM R3). It assesses five leadership competencies (people management & growth, hiring & team building, delivery & execution, cross-functional collaboration & influence, conflict resolution & decision-making) captured as required notes; IC dimensions are often marked N/A.
- **Junior handling differs by pipeline.** External Junior skips System Design (3 rounds). Internal Junior keeps all 3 internal rounds, including System Design. (EM is not leveled J/S/St — it is calibrated by scope: single-team EM vs multi-team / Senior EM.)
- **Every round is 60 minutes** = 10 min intros/candidate questions + 50 min interview. This phrasing is repeated verbatim in each round's Format section; keep it identical.
- **The six scorecard dimensions are fixed and used in every round:** Code quality, Testing strategy, Cloud knowledge, Design and architecture, AI knowledge, Communication. Rated 1–4 (1 = strong no … 4 = strong yes), N/A only when not surfaced. Each round's Evaluation Criteria must reference these same six and align with the per-module "Emphasis by round / module" table in `evaluation/Scorecards.md`. Note: **team & culture fit** (HM round) and **technical taste** (folded into Code quality / Design) are *not* separate scored dimensions — team & culture fit is captured as a required qualitative note, like level fit.
- **Levels:** Junior, Senior, Staff on the IC ladder; Engineering Manager is calibrated by scope instead. Most module sections carry a Level Calibration block — keep the IC levels present where they apply (Junior System Design is explicitly marked "(round not scheduled.)" for External), and add an EM bullet to any module EM candidates take.

A change in one place (e.g. adjusting which dimensions a round emphasizes, or session length) almost always requires matching edits in the overview matrix and expectations table (`HiringOverview.md`), the round's own file (`rounds/*.md`), and the `evaluation/Scorecards.md` tables. Grep across all files for the repeated phrasing before assuming an edit is local.

## Conventions

- US-style section numbering with `#`/`##`/`###`; `---` horizontal rules separate major sections.
- Round content follows a consistent four-part shape: **Overview → Format → Evaluation Criteria → Level Calibration**. Match this when adding or editing rounds.
- Use the existing bold-label bullet style (e.g. `* **Duration:** ...`) rather than introducing new formatting.
