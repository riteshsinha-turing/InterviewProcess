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

* CS / IT / related engineering degree preferred (No BBA, MBA Or Diploma based Degree. We need full regular academic like **B.Tech / M.Tech**.
* Prefer **IIT / NIT / IIIT / Govt.Institutions / Top-Tier institutes** OR demonstrable product impact at scale (**Tier-2 + strong product companies is a valid path**).
* Academics are a **signal**, not a veto — weight work outcomes more heavily for Senior and Staff.

---

## Junior Engineer (4+ YOE)

### Work Experience

* Experience in **product engineering** organizations preferred.
* Strong coding fundamentals (DSA, OOPs, DBMS, OS, networking basics).
* Exposure to distributed systems, cloud platforms (AWS/GCP/Azure), and backend/API development.
* Resume Signals:
  - Impact-oriented projects.
  - ownership beyond assigned tasks.
  - Self-driven mindset.

### AI Forward
- LLMs,GenAI
- AI agents, agentic workflows (bonus).
---

## Senior Engineer (8+ YOE)

### Work Experience

* Experience in scalable product companies preferred.
* Proven ownership: end-to-end delivery, production debugging, mentoring juniors.
* Strong distributed systems and cloud engineering; solid code quality and design practices.
* Resume signals: scale metrics, architecture participation, reliability improvements, cross-functional collaboration; microservices/platform.

### AI Forward

* AI/LLM platform integrations.

---

## Staff Engineer (10+ YOE)

### Work Experience

* Experience driving architecture and technical direction across multiple services or teams.
* Technical leadership: cross-team influence, platform/system evolution, raising engineering standards.
* Deep distributed systems and cloud-native architecture; strong engineering judgment.
* Resume signals: multi-team technical direction, migrations/modernization, reliability/performance ownership, mentoring Seniors, standards and design docs that others adopt.

### AI Forward 

* AI platform architecture.
* Agentic systems / LLM infrastructure.

---
>Candidate must not be AI Passanger - This is interview reigour responsibility to ensure they are not passanger (Without AI they must not feel they are handicapped.)

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

- Round **1** differs by candidate type (external: AI-enabled coding; internal: code walkthrough).
- Rounds **2, 3, and 4** are **shared** by external and internal candidates. **Juniors skip Round 3**; Senior and Staff complete all four rounds.

**All rounds:** 60 minutes total (10 min introductions and candidate questions · 50 min interview).

---

## External Candidates — Round 1

### Round 1 — AI-Enabled Coding & Problem Solving *(External only)*

* **Overview**
  * Evaluate how the candidate solves problems **with AI tools** — not rote DSA recall under a no-AI constraint.
  * Assess problem decomposition, engineering judgment, and ownership of the final solution.
  * Replaces traditional live coding for external candidates; primary signal for coding and AI collaboration.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **AI-allowed:** Tell candidates explicitly that AI tools are allowed (e.g. Cursor, Copilot, ChatGPT, Claude).
  * **Screen share:** Candidate shares screen for the full session; interviewer observes tooling, prompts, and edits.
  * **Problem:** Interviewer provides one level-appropriate coding problem; candidate may use any allowed AI assistant.
  * **Tooling:** Video call with screen share; HackerRank / CoderPad optional for running code — evaluate workflow, not autograding alone.
  * **Problem bank:**
    * Junior — one medium problem (LC-style acceptable).
    * Senior — one medium with extension, or one hard with pragmatic scope.
    * Staff — one hard or medium with substantial extension (scale, failure modes, API shape).
    * Problems must require human verification; avoid pure recall trivia.
* **Evaluation Criteria**
  * Score all six standard dimensions (see §3); emphasize **code quality**, **testing strategy**, **AI knowledge**, **communication**.
  * **Code quality:** Clean, compilable code; refactors and owns the final solution.
  * **Testing strategy:** Runs tests, sanity-checks logic, catches edge cases.
  * **AI knowledge:** Breaks down the problem before prompting; specific iterative prompts; validates output; catches AI bugs and hallucinations; explains when not to use AI shortcuts.
  * **Design and architecture:** Discusses time/space and structural tradeoffs where relevant.
  * **Cloud knowledge:** N/A unless problem touches infra — mark N/A if not probed.
  * **Communication:** Thinks aloud, responds to hints, explains decisions clearly.
* **Level Calibration**
  * **Junior:** One medium problem; clear breakdown and validation; correct solution; acceptable prompting with light guidance.
  * **Senior:** Medium with extension; strong prompting and bug-catching; production-minded structure and tests; discusses tradeoffs.
  * **Staff:** Harder problem or meaningful extension; drives AI workflow intentionally; deep tradeoff discussion; refactors generated code to production quality.

---

## Internal Candidates — Round 1

### Round 1 — Code Walkthrough *(Internal only)*

* **Overview**
  * Evaluate real engineering work through a guided walkthrough of **two internal projects** (PRs, code, or owned modules).
  * Assesses problem understanding, implementation choices, and day-to-day engineering quality.
  * Replaces external Round 1 for internal candidates; not a live coding round.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Preparation:** Candidate (or HM) shares 2 projects and links **at least 24 hours before**; interviewer reviews ahead of time; HM confirms permission to discuss work product.
  * **Walkthrough:** ~25 minutes per project during the 50-minute block; candidate presents, interviewer probes.
  * **Per project, candidate covers:**
    * Problem — what was being solved.
    * Context — team, constraints, timeline, dependencies.
    * Implementation strategy — approach, alternatives, key decisions.
  * **Tooling:** Video call with screen share of internal Git hosting, IDE, or design docs.
* **Evaluation Criteria**
  * Score all six standard dimensions (see §3); emphasize **code quality**, **testing strategy**, **design and architecture**, **communication**.
  * **Code quality:** Readability, structure, maintainability in real contributions.
  * **Testing strategy:** Coverage, test types, confidence in changes.
  * **Design and architecture:** Appropriateness of approach, tradeoffs, coupling.
  * **Cloud knowledge:** Infra or deployment choices in their work, if applicable.
  * **AI knowledge:** Use of AI tools in their workflow, if applicable — otherwise N/A.
  * **Communication:** Depth of ownership; defends decisions; articulates limitations and what they’d do differently.
* **Level Calibration**
  * **Junior:** Clear explanation of scoped work; reasonable code quality and basic tests.
  * **Senior:** Strong ownership narrative; thoughtful design and testing; production awareness.
  * **Staff:** Cross-team or high-impact work; raises engineering standards; articulates systemic tradeoffs.

---

## Shared Rounds (External R2–R4 / Internal R2–R4)

### Round 2 — PR Review & Practical Engineering

* **Overview**
  * Assess engineering judgment, code review capability, and collaboration signals.
  * Simulates day-to-day PR review — bugs, design, tests, security, and maintainability.
  * Shared by external and internal candidates (internal Round 2).
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Exercise:** Level-appropriate canned PR review (GitHub-style or shared IDE / document).
  * **Discussion topics:** Refactoring, API design, testing strategy, readability, reliability/security.
  * **Behavioral probes:** Incident ownership, disagreeing with reviewers, mentoring.
  * **PR bank:** Versioned PRs per level (buggy Junior, leaky abstraction Senior, standards/scale Staff); refresh quarterly; calibrate interviewers before use.
  * **Internal note:** Prefer **synthetic or anonymized PR** when exercise PRs would bias reviewers who were original authors.
* **Evaluation Criteria**
  * Score all six standard dimensions (see §3); emphasize **code quality**, **testing strategy**, **design and architecture**, **communication**.
  * **Code quality:** Severity ordering (block vs comment); bug and flaw detection; maintainability feedback.
  * **Testing strategy:** Gaps in tests identified; suggests meaningful test additions.
  * **Design and architecture:** API shape, coupling, scalability of the change.
  * **Cloud knowledge:** Infra, config, or deployment concerns in the PR, if present.
  * **AI knowledge:** N/A unless PR or discussion touches AI — mark N/A if not probed.
  * **Communication:** Pragmatic decisions; constructive review tone; clear rationale.
* **Level Calibration**
  * **Junior:** Basic correctness and readability feedback; catches obvious bugs.
  * **Senior:** Architecture-aware review depth; security and scale considerations.
  * **Staff:** Organizational standards, rollout risk, and cross-team impact.

---

### Round 3 — Distributed Systems & Engineering Depth

* **Overview**
  * Evaluate how systems **fail, operate, and scale in production** — distinct from Round 4’s “what to build and why.”
  * Scenario-driven depth on distributed systems, cloud, and operational excellence.
  * **Junior:** Round 3 is **not required** — do not schedule; cover light fundamentals in Round 4 if needed.
  * **Senior & Staff:** Required.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Style:** Whiteboarding, architecture diagrams, scenario-driven discussion.
  * **Topics:** Distributed systems fundamentals; scalability and reliability; caching, queues, consistency; databases and storage; cloud infrastructure; observability and debugging; production incidents; optional AI/LLM infrastructure.
  * **Internal note:** May use candidate’s **internal production experience** (incidents, services owned) alongside scenarios.
* **Evaluation Criteria**
  * Score all six standard dimensions (see §3); emphasize **cloud knowledge**, **design and architecture**, **communication**.
  * **Cloud knowledge:** AWS/GCP/Azure concepts; scaling, reliability, observability; production debugging.
  * **Design and architecture:** Tradeoff analysis; consistency models; system boundaries.
  * **Code quality:** N/A unless discussing concrete implementation — mark N/A if not probed.
  * **Testing strategy:** Testing or validation strategies for distributed behavior, if discussed.
  * **AI knowledge:** Optional LLM/AI infra topics if relevant to role.
  * **Communication:** Simplifies complex systems; structured reasoning under follow-ups.
* **Level Calibration**
  * **Junior:** *(Round not scheduled.)*
  * **Senior:** Strong operational and system depth; real-world examples.
  * **Staff:** Deep cross-service tradeoffs; operational excellence at scale.

---

### Round 4 — Hiring Manager (System Design & Leadership)

* **Overview**
  * Assess **what to build, why, and how to own it** — architecture intent, business alignment, leadership, and level fit.
  * Hiring manager or senior leader leads; includes explicit **level fit** recommendation.
  * **Junior:** May include light systems fundamentals (Round 3 skipped).
  * **Internal note:** Include promotion scope; align with performance history and manager input.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Style:** Whiteboarding, architecture diagrams, deep technical and behavioral discussion.
  * **Topics:** System design and architecture evolution (12–24 months); scalability and technical decisions; ownership, stakeholders, mentoring; execution under ambiguity.
  * **Behavioral:** Conflict with PM/design; being wrong technically; driving consensus.
* **Evaluation Criteria**
  * Score all six standard dimensions (see §3); emphasize **design and architecture**, **cloud knowledge**, **communication**.
  * **Design and architecture:** Quality of design; decision framework; evolution and ownership.
  * **Cloud knowledge:** Infra choices, scale path, reliability, and cost tradeoffs in the design.
  * **Code quality:** Structural and API choices in the design — not line-level coding.
  * **Testing strategy:** How they would validate and roll out the system.
  * **AI knowledge:** AI/LLM integration in the design, if relevant to role.
  * **Communication:** Influence, stakeholder alignment, leadership maturity; clear level-fit signal.
* **Level Calibration**
  * **Junior:** Ownership potential and growth mindset; light design scope.
  * **Senior:** Independent technical leadership on a pod/area.
  * **Staff:** Cross-team technical direction without org-wide executive mandate.

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
