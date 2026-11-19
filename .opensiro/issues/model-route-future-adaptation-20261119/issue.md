# metaswarm — optional S4 model-route adaptation constructor (OpenSiro)

**PLAN_ONLY · human-facing proposed Issue · DRAFT — NOT PUBLISHED**

**Target transition:** S4=P -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[roadmap.md](roadmap.md) · [constructor-sufficiency.md](constructor-sufficiency.md).

## Why this exists

Metaswarm already orchestrates software delivery, tests and review. Its original developer-owned model configuration and forthcoming coder-tier routing are valuable, but a prospective, cross-task response to a changing model/provider environment is a different, narrowly bounded experiment. This is a *proposal-stage architectural hypothesis*, not a bug, maintainer request, observed model failure, or shipped C implementation.

Source baseline: [original main](https://github.com/dsifry/metaswarm/tree/4bbb10abd301b9ec9d63371e296049cbc6043baa) pinned 4bbb10abd301b9ec9d63371e296049cbc6043baa, reviewed 2026-11-19. [Included historical Index assessment](https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/me/metaswarm.md), blob 0f94c988125b87fff928898f8d849bfc21875cf7, review_ref 4bbb10abd301b9ec9d63371e296049cbc6043baa, reviewed 2026-11-18, Profile 0.2.4 / Methodology 0.3.8. Index main pin c2e43bf4750841277b3e58d8ba80314121734764; exact catalog row 1251 matched. **Historical VSM vector: S1=A · S2=A · S3=A · S3*=A · S4=P · S5=—**, not reclassified by this roadmap.

## Six organizational functions: historical evidence and current source

| Function / plain-language role | Historical | Current source-backed closure | Priority |
| --- | --- | --- | --- |
| **S1 · Operations** | A | [Coding and other specialists](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/coder.md) execute software work; [start skill](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/start/SKILL.md) invokes relevant roles. | DEFER: no new operations owner required. |
| **S2 · Coordination** | A | [Swarm coordinator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/swarm-coordinator-agent.md) allocates worktrees, prevents collisions and balances concurrent workers. | DEFER: shipped conflict controls. |
| **S3 · Current management** | A | [Orchestrated execution](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/orchestrated-execution/SKILL.md) controls present phases, review and rework. | DEFER: per-task coder tiers are native original work in PR #116. |
| **S3* · Independent audit** | A | [Fresh adversarial reviewers](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/adversarial-reviewer.md) return test/rubric findings. | DEFER: reviewer feedback already exists. |
| **S4 · Future adaptation** | P | [Metrics agent](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/metrics-agent.md), [update](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/update.md) and [role config](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/templates/models.yaml) inform owner-directed decisions; agent-owned prospective model strategy plus later S3 feedback is not verified. | P0: optional S4 C construction hypothesis, not an assumed defect. |
| **S5 · Ultimate identity/policy** | — | Human/maintainer controls project goals, model permissions and budget; agent configuration cannot grant ultimate authority. | NO_TARGET: preserve parent S5; intent for all other omissions UNKNOWN. |

Ownership letters are **not** quality scores. A/P may be intentionally appropriate. The supported system boundary is one installed project delivery cell; providers, hosts and maintainer governance are outside.

## Proposed original-native operator outcome

**Scenario (HYPOTHETICAL):** A supported model becomes unavailable or its price changes before future coding work. A developer who already authorizes a bounded set of role-model routes wants metaswarm to compare valid alternatives for the next task, try one with current S3 approval, capture the real result and revise future advice. No actual provider incident or savings is asserted.

**P0:** Add an opt-in developer-composable S4 contract: dated host/provider evidence + allowed options; model-backed selection between keep/try supported route/escalate; a guarded S3 trial on the *next real task*; results from independent review and usage returned to the selecting S4 actor. No silent overwrite of the owner's models.yaml, automatic installs or new credentials.

**P1:** Pin and reconcile original [Issue #56](https://github.com/dsifry/metaswarm/issues/56) (host-native role models), [PR #116](https://github.com/dsifry/metaswarm/pull/116) (current-task coder tiers, OPEN at review), then implement only the missing prospective integration/rights guards and matched tests. **P2:** optional cost calibration or broader host coverage after a successful experiment.

## Original-first overlap: Track A versus Track B

| C-sufficiency link | Track A already shipped / original native | Track B optional on top |
| --- | --- | --- |
| External/future signal | [models.yaml](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/templates/models.yaml), [update](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/update.md), adapter health and metrics; #56 aims for host role mapping. | Date/source-stamped provider/host change and developer-approved alternatives. |
| Autonomous strategy choice | [PR #116](https://github.com/dsifry/metaswarm/pull/116) selects tiers from **current task** characteristics; user may manually select models. | Future-facing model-backed keep/try/escalate decision within a scoped owner envelope. |
| Lawful S3 action and feedback | [Existing orchestrator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/orchestrated-execution/SKILL.md) can execute/review tasks; [generator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/bin/metaswarm-agents.sh) checks and protects generated roles. | Staged non-destructive next-task route, S3 accept/veto, actual review/usage receipt and return to S4 for retain/revise. |

**Native comparator:** User edits/approves models.yaml, regenerates/checks agent files and uses the original tier rubric if it lands. No new S4 construction is justified if this already produces the same real result more safely or cheaply. Avoid duplicating #56 or #116.

## Proposed sufficiency / acceptance

The complete **proposed** C path is: external future signal → source-backed alternatives → first-party configurable model-backed S4 choice → rightfully applied S3 future work route → real later task/review evidence → feedback to the same strategy actor. Missing any decisive link falsifies the claim. Test positive supported model options and one next-task run. Test negative stale signal, model unavailable, owner veto, hand-edited file, absent valid alternative and reviewer failure. Compare against manual native model selection; no invented fixed test quota.

**Validation state:** NOT_RUN. **Cost:** NOT_MEASURED. This is **GO + NEEDS_EVIDENCE** only at proposal stage. Existing accepted Index grade S4=P remains unchanged. If additional improvement is disproven, the new case becomes scoped NO_GO, not a critique of the harness.

The prior [cross-pack learning NO_GO](https://github.com/opensiro-contributions/metaswarm/blob/opensiro/meta/.opensiro/issues/cross-pack-learning-20261118/roadmap.md) concerns original #52 and remains intact; this is not an attempt to reverse it.

## Decision and publication

The plan is stored privately as OpenSiro-attributed fork metadata on opensiro/meta only; GitHub makes that branch viewable publicly, but **no public fork GitHub Issue/PR or original maintainer message has been created or authorized**. An exact new approval is required for the destination, action, title and full text before publication. Original MIT license and [CONTRIBUTING.md](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/CONTRIBUTING.md) reviewed. Current fork owner control ACTIVE/ALLOW authorizes this internal metadata write, not source changes. No maintainer demand for this particular idea is claimed.

Further implementation requires native host checks and explicit user rights. This draft was AI-assisted; no live model benchmark or independent human implementation review is claimed.
