[← Hiring Overview](../HiringOverview.md)

# Scorecards & Hiring Decision

## Standard Scorecard (Per Round)

Use the **same six dimensions** for every interview round. Rate each **1–4** (1 = strong no, 2 = no, 3 = yes, 4 = strong yes). Mark **N/A** only if the round truly did not surface that dimension.

| Dimension | What to assess |
|-----------|----------------|
| **Code quality** | Readability, structure, correctness, maintainability, refactoring judgment, technical taste |
| **Testing strategy** | Test coverage, test types, confidence in changes, TDD/debug discipline |
| **Cloud knowledge** | AWS/GCP/Azure, infra concepts, scalability, reliability, observability, production operations |
| **Design and architecture** | System design, tradeoffs, API/service boundaries, evolution and ownership |
| **AI knowledge** | Effective use of AI tools (external R1), prompting/validation, AI/LLM platform or product integration where relevant |
| **Communication** | Clarity, structure, collaboration, receptiveness to feedback, explains decisions well |

### Emphasis by round / module (what to probe)

| Round / module | Primary dimensions |
|----------------|-------------------|
| **[AI-enabled coding](../rounds/ai-enabled-coding.md)** (External R1) | Code quality, testing strategy, AI knowledge, communication |
| **[Code walkthrough](../rounds/code-walkthrough.md)** (Internal R1 option) | Code quality, testing strategy, design and architecture, communication |
| **[PR Review and Code Comprehension](../rounds/pr-review-and-code-comprehension.md)** (External R2 / Internal R1 option / EM R1) | Code quality, testing strategy, design and architecture, communication |
| **[System Design - Distributed Systems](../rounds/system-design-distributed-systems.md)** (Ext R3 / Int R2 / EM R2) | Cloud knowledge, design and architecture, communication |
| **[Engineering Leadership](../rounds/engineering-leadership.md)** (EM R3) | Communication, design and architecture (technical judgment) · plus leadership-competency notes |
| **[HM - Technical Taste and Fit](../rounds/hm-technical-taste-and-fit.md)** (Ext R4 / Int R3 / EM R4) | Design and architecture, communication, code quality (taste) · plus team & culture fit note |
| **[Test Automation Coding & Framework Design](../rounds/test-automation-coding.md)** (SDET R1) | Code quality, testing strategy, design and architecture, AI knowledge, communication |
| **[Test Strategy, CI/CD & Quality Engineering](../rounds/test-strategy-and-ci.md)** (SDET R2) | Testing strategy, cloud knowledge, design and architecture, communication · plus team & culture fit note |

**Required per round (in addition to scores above):**

* Overall recommendation: Hire / Lean Hire / Lean No / No Hire
* **Level fit** — IC ladder (J / S / St); for Engineering Manager candidates, EM-track scope (single-team EM / multi-team or Senior EM); for SDET candidates, the SDET bar (solid / strong).
* Top strengths, top risks, open questions
* **HM round additionally:** a qualitative **team & culture fit** read.
* **Engineering Leadership round additionally:** structured notes on the five leadership competencies (people management & growth, hiring & team building, delivery & execution, cross-functional collaboration & influence, conflict resolution & decision-making).

## Debrief & Leveling Policy

* **Attendees:** Hiring manager + all interviewers (minimum 30 minutes within 48 hours of final round).
* **Level rule:** Hire level ≤ demonstrated level in **≥2 of 3 rounds** (Junior, and all internal candidates) or **≥3 of 4 rounds** (external Senior & Staff, and Engineering Managers). **SDET:** a hire requires a positive signal in **both** rounds.
* **Veto:** Any **No Hire on the first round** (AI-enabled coding for external; code walkthrough or PR review for internal; PR review for EM; Test Automation Coding & Framework Design for SDET) is a veto for all levels. **No Hire on System Design - Distributed Systems** is a **strong veto** for Senior & Staff (external and internal) and for Engineering Managers, unless documented override with VP alignment. For **Engineering Manager** candidates, a **No Hire on Engineering Leadership is a veto**.
* **No “average of averages”** — discuss conflicting signals explicitly; do not level up on the HM round alone.
* **Decision:** Documented hire / no-hire / hold with level and dissent notes.
