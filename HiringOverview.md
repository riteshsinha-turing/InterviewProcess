# IC Engineering Hiring Process (Bangalore, India — In-Office)

This is the **overview and index**. Detailed criteria live in linked documents:

* **[Resume Screening Criteria](screening/ResumeScreening.md)** — per-level sourcing guidelines for recruiters.
* **[Scorecards & Hiring Decision](evaluation/Scorecards.md)** — the six-dimension scorecard, per-round emphasis, and debrief/leveling policy.
---

## Job Descriptions

Portal-ready job descriptions for open roles (LinkedIn, Naukri, Instahyre, careers page, etc.), each self-contained and copy-paste ready. They are derived from the [Resume Screening Criteria](screening/ResumeScreening.md) and the rounds below — keep them in sync when criteria change.

| Role | Experience | File |
|------|-----------|------|
| Software Engineer | 2–4 years | [JobDescription/software-engineer.md](JobDescription/software-engineer.md) |
| Senior Software Engineer | 6–8 years | [JobDescription/senior-software-engineer.md](JobDescription/senior-software-engineer.md) |
| Staff Engineer | 8–12 years | [JobDescription/staff-engineer.md](JobDescription/staff-engineer.md) |
| Engineering Manager | 8–12 years (incl. 3+ in leadership) | [JobDescription/engineering-manager.md](JobDescription/engineering-manager.md) |
| SDET (Automation Testing) | 5+ years | [JobDescription/sdet.md](JobDescription/sdet.md) |

**Common to all roles:** Bangalore, India · in-office · hybrid.

---

## Process Overview

| Candidate type | Round 1 | Round 2 | Round 3 | Round 4 |
|----------------|---------|---------|---------|---------|
| **External** | [AI-enabled coding & problem solving](rounds/ai-enabled-coding.md) | [PR review and code comprehension](rounds/pr-review-and-code-comprehension.md) | [System Design - Distributed Systems](rounds/system-design-distributed-systems.md) | [HM - Technical Taste and Fit](rounds/hm-technical-taste-and-fit.md) |
| **Internal** | [Code walkthrough](rounds/code-walkthrough.md) **or** [PR review](rounds/pr-review-and-code-comprehension.md) *(choice)* | [System Design - Distributed Systems](rounds/system-design-distributed-systems.md) | [HM - Technical Taste and Fit](rounds/hm-technical-taste-and-fit.md) | — *(not used)* |
| **Engineering Manager** | [PR review and code comprehension](rounds/pr-review-and-code-comprehension.md) | [System Design - Distributed Systems](rounds/system-design-distributed-systems.md) | [Engineering Leadership](rounds/engineering-leadership.md) | [HM - Technical Taste and Fit](rounds/hm-technical-taste-and-fit.md) |
| **SDET (Automation Testing)** | [Test Automation Coding & Framework Design](rounds/test-automation-coding.md) | [Test Strategy, CI/CD & Quality Engineering](rounds/test-strategy-and-ci.md) | — | — |

### Rounds by level

| Level | External | Internal |
|-------|----------|----------|
| **Junior** | 3 rounds — skip System Design (R1 → R2 → R4) | 3 rounds — all (R1 → R2 → R3) |
| **Senior** | 4 rounds — all | 3 rounds — all |
| **Staff** | 4 rounds — all | 3 rounds — all |

*The Junior/Senior/Staff levels above are the **IC ladder**. **Engineering Manager** (management track) and **SDET** (automation testing track) are separate single-profile tracks — see their pipelines below.*

* **External Round 1** — AI-allowed live coding; evaluate how candidates work with AI tools, not memorized DSA alone.
* **Internal Round 1** — candidate's (or HM's) choice of a **code walkthrough** of two internal projects/PRs **or** a **PR review** exercise; evaluate problem understanding, implementation, and engineering quality.
* **External pipeline:** Junior R1 → R2 → R4 (HM), skipping System Design; Senior and Staff use all four rounds.
* **Internal pipeline:** all levels run three rounds — R1 (walkthrough or PR review) → R2 (System Design - Distributed Systems) → R3 (HM - Technical Taste and Fit). Internal Juniors **do** complete the System Design round.
* **Engineering Manager pipeline:** a fixed **4-round** loop — R1 (PR review and code comprehension) → R2 (System Design - Distributed Systems) → R3 (Engineering Leadership) → R4 (HM - Technical Taste and Fit). Calibrated on the **EM scope** (single-team vs multi-team), not the IC ladder.
* **SDET (automation testing) pipeline:** a focused **2-round** loop — R1 (Test Automation Coding & Framework Design) → R2 (Test Strategy, CI/CD & Quality Engineering). Single profile (5+ YOE), not the IC ladder.
* **Session length:** Every interview round is **60 minutes** — **10 minutes** introductions and candidate questions; **50 minutes** for the interview.
* Include **production/debugging** and **collaboration** probes in every round where applicable.

---

## Level-Specific Round Expectations

Columns are interview **modules**; where a module sits in each pipeline is noted in the header. Internal Round 1 expectations are covered by the **code walkthrough** and **PR review** columns (candidate does one).

| Level | [AI-enabled coding](rounds/ai-enabled-coding.md) *(Ext R1)* | [Code walkthrough](rounds/code-walkthrough.md) *(Int R1 option)* | [PR review](rounds/pr-review-and-code-comprehension.md) *(Ext R2 / Int R1 option)* | [System Design](rounds/system-design-distributed-systems.md) *(Ext R3 / Int R2)* | [HM - Technical Taste and Fit](rounds/hm-technical-taste-and-fit.md) *(Ext R4 / Int R3)* |
|-------|------------------------------|------------------------------------|--------------------------------------|---------------------------------------------------------|--------------------------------------------------|
| **Junior** | 1 medium problem; clear breakdown, validates AI output, working solution | 2 projects; explains context and approach; solid code quality for scope | Basic correctness and readability feedback; catches obvious bugs | *Ext: skipped.* Int: fundamentals + light design, examples from owned work | Growth + ownership potential; light design and taste; team fit |
| **Senior** | Medium + extension; strong prompting, catches AI mistakes, discusses tradeoffs | 2 projects; depth on design and testing; ownership visible | Architecture-aware depth; security and scale considerations | Operational and architecture depth; real-world examples | Design, technical taste, and ownership; clear team & culture fit |
| **Staff** | Harder problem or extension; owns AI workflow, refactors generated code | 2 projects; cross-cutting impact, standards, tradeoffs articulated | Standards, scale, rollout risk; cross-team impact | Cross-service tradeoffs; operational excellence at scale | Cross-team influence, deep technical taste, design; culture leadership |

*This table covers the IC ladder. **Engineering Manager** candidates run a fixed 4-round loop (PR review → System Design → Engineering Leadership → HM) calibrated on EM scope — see [Engineering Leadership](rounds/engineering-leadership.md).*

---

## How the Rounds Fit Together

**Round 1 differs by candidate type:**

* **External Round 1** — [AI-enabled coding & problem solving](rounds/ai-enabled-coding.md).
* **Internal Round 1** — candidate's (or HM's) choice of [code walkthrough](rounds/code-walkthrough.md) or [PR review](rounds/pr-review-and-code-comprehension.md).
* **EM Round 1** — [PR review and code comprehension](rounds/pr-review-and-code-comprehension.md).

After Round 1, **external** candidates continue through PR review, System Design - Distributed Systems, and the HM round (Senior & Staff; Juniors skip System Design). **Internal** candidates continue through System Design - Distributed Systems and the HM round — three rounds total at every level. **Engineering Manager** candidates run a fixed 4-round loop and add the EM-only [Engineering Leadership](rounds/engineering-leadership.md) round before the HM round.

**SDET (automation testing)** candidates run a focused 2-round loop of their own: [Test Automation Coding & Framework Design](rounds/test-automation-coding.md) (R1) → [Test Strategy, CI/CD & Quality Engineering](rounds/test-strategy-and-ci.md) (R2). Both rounds are SDET-specific and are not shared with the other pipelines.

**All rounds:** 60 minutes total (10 min introductions and candidate questions · 50 min interview).
