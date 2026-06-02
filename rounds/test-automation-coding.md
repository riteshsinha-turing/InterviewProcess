[← Hiring Overview](../HiringOverview.md) · [Scorecards & Hiring Decision](../evaluation/Scorecards.md)

# Test Automation Coding & Framework Design

*Pipeline placement: **SDET Round 1** (automation testing candidates only).*

* **Overview**
  * Hands-on assessment of the candidate's ability to **write robust automated tests and design test framework code** for real frontend and backend scenarios.
  * Primary signal for automation craft — clean test code, sound abstractions, and flake-resistant design, not record-and-playback scripting.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **AI-allowed:** AI tools are explicitly allowed (e.g. Cursor, Copilot, ChatGPT, Claude), consistent with our AI-forward stance; evaluate how the candidate uses and validates them.
  * **Screen share:** Candidate shares screen for the full session; interviewer observes tooling, prompts, and edits.
  * **Exercise:** Automate a given scenario — e.g. UI tests for a small web flow (Playwright/Selenium/Cypress) and/or API/integration tests for an endpoint, or extend a starter test framework. Candidate may use their preferred framework.
  * **Probe:** Locator strategy, synchronization/waits, flakiness mitigation, test data setup/teardown, assertion design, UI-vs-API test split, reusable abstractions (page objects, fixtures), and parallelization-readiness.
  * **Tooling:** Video call with screen share; shared IDE / repo / CoderPad for running tests — evaluate workflow and code, not autograding alone.
* **Evaluation Criteria**
  * Score all six standard dimensions (see [Scorecards](../evaluation/Scorecards.md)); emphasize **code quality**, **testing strategy**, **design and architecture**, **AI knowledge**, **communication**.
  * **Code quality:** Clean, readable, maintainable test code; reusable abstractions rather than brittle, copy-pasted scripts.
  * **Testing strategy:** Meaningful coverage and edge cases; tests at the right level (UI/API/unit); deterministic, flake-resistant assertions.
  * **Design and architecture:** Framework and abstraction design — page objects, fixtures, data builders, separation of concerns.
  * **Cloud knowledge:** N/A unless the exercise touches CI — pipeline depth is covered in Round 2.
  * **AI knowledge:** Effective, validated use of AI to accelerate test authoring; catches AI mistakes and brittle generated selectors.
  * **Communication:** Thinks aloud, explains tradeoffs and approach, responds to hints.
* **Bar (SDET, 5+ YOE)**
  * **Solid:** Working, reasonably structured automated tests; sensible locators and waits; basic reuse; catches obvious flakiness.
  * **Strong:** Clean framework design and abstractions; proactively addresses flakiness, test data, and parallelization; pragmatic UI-vs-API choices; production-quality test code.
