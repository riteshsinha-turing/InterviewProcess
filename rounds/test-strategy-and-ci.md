[← Hiring Overview](../HiringOverview.md) · [Scorecards & Hiring Decision](../evaluation/Scorecards.md)

# Test Strategy, CI/CD & Quality Engineering

*Pipeline placement: **SDET Round 2** (automation testing candidates only). Final round — HM-led; includes team & culture fit.*

* **Overview**
  * Assess how the candidate thinks about **quality at the system level** — test strategy, CI/CD automation, suite reliability, and cross-functional collaboration.
  * The closing round: led by the hiring manager (or senior QE), it produces the **level/bar fit** recommendation and a **team & culture fit** read.
* **Format**
  * **Duration:** 60 minutes total — 10 minutes introductions and candidate questions; 50 minutes for the interview.
  * **Style:** Discussion and whiteboarding, scenario-driven; may draw on the candidate's real experience.
  * **Topics:**
    * **Test strategy** — the test pyramid, what/when to automate vs. leave manual, automation ROI, regression prevention, shift-left.
    * **CI/CD pipelines** — designing a pipeline (e.g. **GitHub Actions**): triggers, stages, test sharding/parallelization, artifacts and reporting, merge gating, environments and test data.
    * **Suite reliability** — flaky-test detection and management, quarantine strategy, debugging failing pipelines, keeping the suite fast and trustworthy.
    * **Quality metrics** — coverage, pass rate, mean-time-to-diagnose test failures.
    * **Collaboration** — partnering with developers, advocating for testability, owning release quality.
  * **Behavioral:** Ownership of quality; disagreeing with developers on coverage; driving testability improvements.
* **Evaluation Criteria**
  * Score all six standard dimensions (see [Scorecards](../evaluation/Scorecards.md)); emphasize **testing strategy**, **cloud knowledge**, **design and architecture**, **communication**.
  * **Testing strategy:** Coherent, pragmatic strategy; sound automation ROI judgment; strong regression and reliability focus.
  * **Cloud knowledge:** CI/CD pipeline design (GitHub Actions or similar), parallelization, environments, reporting/gating.
  * **Design and architecture:** Scalable, maintainable test architecture and pipeline structure.
  * **Code quality:** N/A unless concrete implementation is discussed — mark N/A if not probed.
  * **AI knowledge:** AI-assisted testing or pipeline tooling where relevant.
  * **Communication:** Cross-functional collaboration, influence, clear quality advocacy; team & culture fit signal.
* **Required note:** a qualitative **team & culture fit** read (this is the HM-led closing round).
* **Bar (SDET, 5+ YOE)**
  * **Solid:** Reasonable test strategy and a workable CI pipeline; understands flakiness and basic reporting.
  * **Strong:** Owns quality end-to-end; designs scalable, fast, reliable pipelines; data-driven about suite health; influences developers and shifts testing left.
