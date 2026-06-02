[← Hiring Overview](../HiringOverview.md) · [Scorecards & Hiring Decision](../evaluation/Scorecards.md)

# AI-Enabled Coding & Problem Solving

*Pipeline placement: **External Round 1** (external candidates only).*

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
  * Score all six standard dimensions (see [Scorecards](../evaluation/Scorecards.md)); emphasize **code quality**, **testing strategy**, **AI knowledge**, **communication**.
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
