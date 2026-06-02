[← Hiring Overview](../HiringOverview.md) · [Scorecards & Hiring Decision](../evaluation/Scorecards.md)

# PR Review and Code Comprehension

*Pipeline placement: **External Round 2**, **Internal Round 1 (Option B)**, and **EM Round 1**. One shared module reused across pipelines.*

* **Overview**
  * Assess engineering judgment, code review capability, and collaboration signals.
  * Simulates day-to-day PR review — bugs, design, tests, security, and maintainability.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Exercise:** Level-appropriate canned PR review (GitHub-style or shared IDE / document).
  * **Discussion topics:** Refactoring, API design, testing strategy, readability, reliability/security.
  * **Behavioral probes:** Incident ownership, disagreeing with reviewers, mentoring.
  * **PR bank:** Versioned PRs per level (buggy Junior, leaky abstraction Senior, standards/scale Staff); refresh quarterly; calibrate interviewers before use.
  * **Internal note:** Prefer **synthetic or anonymized PR** when exercise PRs would bias reviewers who were original authors.
* **Evaluation Criteria**
  * Score all six standard dimensions (see [Scorecards](../evaluation/Scorecards.md)); emphasize **code quality**, **testing strategy**, **design and architecture**, **communication**.
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
