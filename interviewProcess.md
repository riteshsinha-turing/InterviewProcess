# IC Engineering Hiring Process (Bangalore, India — In-Office)

---

## Process Overview

| Candidate type | Round 1 | Round 2 | Round 3 | Round 4 |
|----------------|---------|---------|---------|---------|
| **External** | AI-enabled coding & problem solving | PR review & practical engineering | Distributed systems & engineering depth | Hiring manager (system design & leadership) |
| **Internal** | Code walkthrough (internal projects) | PR review & practical engineering | Distributed systems & engineering depth | Hiring manager (system design & leadership) |

### Rounds by level

| Level | Total rounds | Round 3 (Systems) |
|-------|--------------|-------------------|
| **Junior** | 3 | **Not required** — skip Round 3 |
| **Senior** | 4 | Required |
| **Staff** | 4 | Required |

* **External Round 1** — AI-allowed live coding; evaluate how candidates work with AI tools, not memorized DSA alone.
* **Internal Round 1** — code walkthrough of two internal projects/PRs; evaluate problem understanding, implementation, and engineering quality.
* **Junior pipeline:** R1 → R2 → R4 (HM). Senior and Staff use all four rounds.
* **Session length:** Every interview round is **60 minutes** — **10 minutes** introductions and candidate questions; **50 minutes** for the interview.
* Include **production/debugging** and **collaboration** probes in every round where applicable.

---

# 1. Resume Screening Criteria

*Provide these guidelines to recruiters; they own sourcing and funnel through to interview scheduling.*

### Academic Experience (All Levels)

* CS / IT / related engineering degree preferred.
* Prefer IIT / NIT / IIIT / top-tier institutes **or** demonstrable product impact at scale (tier-2 + strong product companies is a valid path).
* Academics are a **signal**, not a veto — weight work outcomes more heavily for Senior and Staff.

---

## Junior Engineer (2–4 YOE)

### Work Experience

* Experience in product engineering organizations preferred.
* Strong coding fundamentals (DSA, OOP, DBMS, OS, networking basics).
* Exposure to distributed systems, cloud platforms (AWS/GCP/Azure), and backend/API development.
* Resume signals: impact-oriented projects, ownership beyond assigned tasks.

### AI Forward

* LLMs, GenAI, AI agents, agentic workflows (bonus).

---

## Senior Engineer (6–8 YOE)

### Work Experience

* Experience in scalable product companies preferred.
* Proven ownership: end-to-end delivery, production debugging, mentoring juniors.
* Strong distributed systems and cloud engineering; solid code quality and design practices.
* Resume signals: scale metrics, architecture participation, reliability improvements, cross-functional collaboration; microservices/platform (bonus).

### AI Forward

* AI/LLM platform integrations (bonus).

---

## Staff Engineer (8–12 YOE)

### Work Experience

* Experience driving architecture and technical direction across multiple services or teams.
* Technical leadership: cross-team influence, platform/system evolution, raising engineering standards.
* Deep distributed systems and cloud-native architecture; strong engineering judgment.
* Resume signals: multi-team technical direction, migrations/modernization, reliability/performance ownership, mentoring Seniors, standards and design docs that others adopt.

### AI Forward

* AI platform architecture (bonus).
* Agentic systems / LLM infrastructure (bonus).

---

# 2. Interview Process

## Level-Specific Round Expectations

| Level | External R1 (AI-enabled coding) | Internal R1 (Code walkthrough) | R2 (PR) | R3 (Systems) | R4 (HM) |
|-------|-------------------------------|--------------------------------|---------|--------------|---------|
| **Junior** | 1 medium problem; clear breakdown, validates AI output, working solution | 2 projects; explains context and approach; solid code quality for scope | — *(not required)* | Growth + light design |
| **Senior** | Medium + extension; strong prompting, catches AI mistakes, discusses tradeoffs | 2 projects; depth on design and testing; ownership visible | Architecture-aware depth | Operational depth | Design + ownership |
| **Staff** | Harder problem or extension; owns AI workflow, refactors generated code | 2 projects; cross-cutting impact, standards, tradeoffs articulated | Standards, scale, rollout risk | Cross-service tradeoffs | Design + cross-team influence |

---

## Interview Rounds

Round **1** differs by candidate type (external: AI-enabled coding; internal: code walkthrough). Rounds **2, 3, and 4** are **shared** by external and internal candidates. **Juniors skip Round 3**; Senior and Staff complete all four rounds.

**All rounds:** 60 minutes total (10 min introductions and candidate questions · 50 min interview).

---

## External Candidates — Round 1

### Round 1 — AI-Enabled Coding & Problem Solving *(External only)*

#### Objective

* Evaluate how the candidate solves problems **with AI tools** — problem decomposition, engineering judgment, and ownership of the final solution — not rote DSA recall under a no-AI constraint.

#### Format

* **AI-allowed live coding round** — tell candidates explicitly that **AI tools are allowed** (e.g. Cursor, Copilot, ChatGPT, Claude).
* Candidate **shares screen** for the full session so the interviewer can observe tooling, prompts, and edits.
* Interviewer provides one coding problem (see Problem Bank Guidance); candidate may use any allowed AI assistant.

#### Duration

* **60 minutes total** — 10 minutes introductions and candidate questions; 50 minutes for the interview.

#### Recommended Format / Tooling

* Video call with **screen share** (candidate’s IDE + AI tool visible).
* HackerRank / CoderPad optional for running code; primary evaluation is live workflow, not platform autograding.

#### What to Evaluate (Score 1–4 Each)

* **Break down the problem** — clarifies requirements, edge cases, and approach before leaning on AI.
* **Prompt the tool** — specific, iterative prompts; uses AI for the right subtasks (not blind paste).
* **Validate the output** — reads generated code, runs tests, sanity-checks logic and complexity.
* **Catch bugs** — finds and fixes AI mistakes, hallucinations, and missed edge cases.
* **Explain tradeoffs** — time/space, design choices, and when *not* to use AI-generated shortcuts.
* **Modify generated code** — refactors, renames, simplifies, and makes the solution their own.

#### Level Calibration

* **Junior:** One medium problem; clear breakdown and validation; arrives at a correct solution with guidance on prompting quality acceptable.
* **Senior:** Medium with extension; strong prompting and bug-catching; discusses tradeoffs; production-minded structure and tests.
* **Staff:** Harder problem or meaningful extension; drives the AI workflow intentionally; refactors generated code; deep tradeoff discussion.

#### Problem Bank Guidance

* **Junior:** One medium problem (LC-style acceptable).
* **Senior:** One medium with extension, or one hard with pragmatic scope.
* **Staff:** One hard or medium with a substantial extension (e.g. scale, failure modes, API shape).
* Problems should be solvable with AI assistance but **require human verification** — avoid pure recall trivia.

---

## Internal Candidates — Round 1

### Round 1 — Code Walkthrough *(Internal only)*

#### Objective

* Evaluate the candidate’s real engineering work through a guided walkthrough of **two internal projects** — problem understanding, implementation choices, and code quality.

#### Preparation

* Candidate (or HM) selects **2 internal projects** — PRs, code areas, or merged work they owned — and shares links/materials **at least 24 hours before** the session.
* Interviewer reviews artifacts ahead of time. HM confirms permission to discuss work product with the panel.

#### Format

* **Code walkthrough** — candidate presents each project; interviewer asks follow-ups.
* Candidate explains for each project:
  * **Problem** — what was being solved.
  * **Context** — team, constraints, timeline, dependencies.
  * **Implementation strategy** — approach, alternatives considered, key decisions.
* **~25 minutes per project** during the 50-minute interview block (two projects).

#### Duration

* **60 minutes total** — 10 minutes introductions and candidate questions; 50 minutes for the interview.

#### Recommended Format / Tooling

* Video call with **screen share** of internal Git hosting, IDE, or design docs.

#### What to Evaluate (Score 1–4 Each)

* **Code quality** — readability, structure, maintainability.
* **Design choices** — appropriateness of approach, tradeoffs, coupling.
* **Testing strategy** — coverage, test types, confidence in changes.
* **Overall understanding** — depth of ownership; can explain and defend decisions; knows limitations and what they’d do differently.

#### Level Calibration

* **Junior:** Clear explanation of scoped work; reasonable code quality and basic tests.
* **Senior:** Strong ownership narrative; thoughtful design and testing; production awareness.
* **Staff:** Cross-team or high-impact work; raises the bar on standards; articulates systemic tradeoffs.

---

## Shared Rounds (External R2–R4 / Internal R2–R4)

### Round 2 — PR Review & Practical Engineering

#### Objective

* Assess engineering judgment, code review capability, and collaboration signals.

#### Topics

* PR/code review exercise (use level-appropriate canned PRs).
* Refactoring, API design, testing strategy.
* Readability, maintainability, reliability/security.
* Behavioral probes: incident ownership, disagreeing with reviewers, mentoring.

#### Duration

* **60 minutes total** — 10 minutes introductions and candidate questions; 50 minutes for the interview.

#### Recommended Format / Tooling

* GitHub-style PR review; shared IDE or document walkthrough.

#### Evaluation Criteria (Score 1–4 Each)

* Severity ordering (block vs comment).
* Bug and design flaw detection.
* Engineering best practices and maintainability.
* Scalability/security attention.
* Pragmatic decision making and communication.

#### Level Calibration

* **Junior:** Basic correctness and readability feedback.
* **Senior:** Architecture-aware review depth.
* **Staff:** Organizational engineering standards, rollout risk, and cross-team impact.

#### Canned PR Guidance

* Maintain **versioned PR banks** per level (buggy Junior PR, leaky abstraction Senior PR, standards/scale Staff PR).
* Refresh problem bank quarterly; calibrate interviewers before first use each cycle.

---

### Round 3 — Distributed Systems & Engineering Depth

* **Junior:** Round 3 is **not required** — do not schedule. Cover foundational systems topics lightly in Round 4 (HM) if needed.
* **Senior & Staff:** Required.

#### Objective

* Evaluate how systems **fail, operate, and scale in production** — distinct from Round 4’s “what to build and why.”

#### Topics

* Distributed systems fundamentals, scalability, reliability.
* Caching, queues, consistency models.
* Databases, storage tradeoffs, cloud infrastructure.
* Observability, debugging, production incident handling.
* Optional AI/LLM infrastructure discussion.

#### Duration

* **60 minutes total** — 10 minutes introductions and candidate questions; 50 minutes for the interview.

#### Recommended Format / Tooling

* Whiteboarding, architecture diagrams, scenario-driven discussion.

#### Evaluation Criteria (Score 1–4 Each)

* Systems thinking and tradeoff analysis.
* Production and debugging depth.
* Real-world engineering experience.
* Ability to simplify complex systems.
* Communication.

#### Level Calibration

* **Junior:** Foundational understanding with curiosity.
* **Senior:** Strong operational and system depth.
* **Staff:** Deep cross-service tradeoffs and operational excellence at scale.

---

### Round 4 — Hiring Manager (System Design & Leadership)

#### Objective

* Assess **what to build, why, and how to own it** — architecture intent, business alignment, leadership, and level fit.

#### Topics

* System design and architecture evolution (12–24 month horizon).
* Scalability planning and technical decision making.
* Engineering ownership, stakeholder management, mentoring.
* Execution under ambiguity; collaboration and influence.
* Behavioral: conflict with PM/design, being wrong technically, driving consensus.

#### Duration

* **60 minutes total** — 10 minutes introductions and candidate questions; 50 minutes for the interview.

#### Recommended Format / Tooling

* Whiteboarding, architecture diagrams, deep technical discussion.

#### Evaluation Criteria (Score 1–4 Each)

* Architecture quality and decision framework.
* Leadership maturity and ownership mindset.
* Business/engineering alignment.
* Communication and influence.
* **Level fit** (explicit hire level recommendation).

#### Level Calibration

* **Junior:** Ownership potential and growth mindset.
* **Senior:** Independent technical leadership on a pod/area.
* **Staff:** Cross-team technical direction without requiring org-wide executive mandate.

---

### Internal Candidate Notes (Rounds 2–4)

* Use the **same scorecards, duration, and level calibration** as the shared round definitions above.
* **Round 2 (PR):** Prefer a **synthetic or anonymized PR** when exercise PRs would bias reviewers who were original authors.
* **Round 3 (Systems):** Required for Senior and Staff only. May draw on **internal production experience** (incidents, services owned) in addition to scenario prompts.
* **Round 4 (HM):** Include promotion scope and level-fit discussion; align with performance history and manager input.

---

# 3. Scorecards & Hiring Decision

## Standard Scorecard (Per Round)

Use the **same six dimensions** for every interview round. Rate each **1–4** (1 = strong no, 2 = no, 3 = yes, 4 = strong yes). Mark **N/A** only if the round truly did not surface that dimension.

| Dimension | What to assess |
|-----------|----------------|
| **Code quality** | Readability, structure, correctness, maintainability, refactoring judgment |
| **Testing strategy** | Test coverage, test types, confidence in changes, TDD/debug discipline |
| **Cloud knowledge** | AWS/GCP/Azure, infra concepts, scalability, reliability, observability, production operations |
| **Design and architecture** | System design, tradeoffs, API/service boundaries, evolution and ownership |
| **AI knowledge** | Effective use of AI tools (external R1), prompting/validation, AI/LLM platform or product integration where relevant |
| **Communication** | Clarity, structure, collaboration, receptiveness to feedback, explains decisions well |

### Emphasis by round (what to probe)

| Round | Primary dimensions |
|-------|-------------------|
| **R1** (external: AI coding; internal: code walkthrough) | Code quality, testing strategy, AI knowledge, communication |
| **R2** (PR review) | Code quality, testing strategy, design and architecture, communication |
| **R3** (systems) | Cloud knowledge, design and architecture, communication |
| **R4** (HM) | Design and architecture, cloud knowledge, communication |

**Required per round (in addition to scores above):**

* Overall recommendation: Hire / Lean Hire / Lean No / No Hire
* **Level fit** (J / S / St)
* Top strengths, top risks, open questions

## Debrief & Leveling Policy

* **Attendees:** Hiring manager + all interviewers (minimum 30 minutes within 48 hours of final round).
* **Level rule:** Hire level ≤ demonstrated level in **≥2 of 3 rounds** (Junior) or **≥3 of 4 rounds** (Senior & Staff).
* **Veto:** Any **No Hire** on Round 1 (AI-enabled coding for external; code walkthrough for internal) is a veto for all levels. **No Hire on Round 3 (systems depth)** is a **strong veto** for Senior & Staff unless documented override with VP alignment.
* **No “average of averages”** — discuss conflicting signals explicitly; do not level up on HM round alone.
* **Decision:** Documented hire / no-hire / hold with level and dissent notes.
