# metaswarm — technical S4 model-route adaptation constructor contract

**Target transition:** S4=P -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

Canonical [roadmap.md](roadmap.md) owns accepted historical vector, six-function dispositions, priority and verdict. Human-readable [issue.md](issue.md) owns the six-row explanatory table. This technical document references those without repeating their tables.

## 1. Scope, pins and independent research status

- Original system: installed dsifry/metaswarm project delivery cell using first-party roles, BEADS orchestration, model configuration, adaptive role resolution and review.
- Frozen original: https://github.com/dsifry/metaswarm/tree/4bbb10abd301b9ec9d63371e296049cbc6043baa (main 2026-11-19, matching the Index review_ref).
- Accepted historical Index: https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/me/metaswarm.md, document blob 0f94c988125b87fff928898f8d849bfc21875cf7, reviewed 2026-11-18, Profile 0.2.4, methodology 0.3.8, status included. There is no current Index re-grade.
- Experiment scope: one authorized project, one supported host and role, one prospective model/provider disturbance, one future work-unit, then returned outcome. Non-claim: external provider release/price incident has been observed.
- Research: Proposed architecture GO, NEEDS_EVIDENCE, native model runs NOT_RUN and matched cost NOT_MEASURED.

## 2. Track A: shipped native behaviors, external issues and PR heads

1. [templates/models.yaml](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/templates/models.yaml): explicit role/host model declarations, with escalation; these are project config, not host-prospective strategic choices.
2. [bin/metaswarm-agents.sh](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/bin/metaswarm-agents.sh): resolves role models and checks or regenerates project-scoped Claude agent files. It detects hand edits and limits forced replacement. Use the existing resolver semantics; never silently rewrite user model settings.
3. [tests/agents/test-adapter-models.sh](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/tests/agents/test-adapter-models.sh): verifies Codex/Gemini adapter health, selected models and fallback. These are baseline tests, not an S4 feedback proof.
4. [agents/metrics-agent.md](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/metrics-agent.md): collects metrics and trends, makes reports/recommendations; its report-to-human path cannot be assumed to update future model policy automatically.
5. [commands/update.md](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/update.md): version lookup and guided update; marketplace auto-update is platform behavior, not a self-governing future strategy choice.
6. [skills/orchestrated-execution/SKILL.md](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/orchestrated-execution/SKILL.md) and [agents/adversarial-reviewer.md](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/adversarial-reviewer.md): existing S3 execution and independent task feedback; reuse rather than writing a rival coordinator.
7. Original [Issue #56](https://github.com/dsifry/metaswarm/issues/56): OPEN host-native per-role model generation; do not preempt or reconstruct its deliverables.
8. Original [PR #55](https://github.com/dsifry/metaswarm/pull/55): MERGED role-type and model configuration.
9. Original [PR #116](https://github.com/dsifry/metaswarm/pull/116): OPEN at b42c52cdb2885e5d2e447d1072700dccf68659ef; inspected its coder agent patch, new [coder-selection guide](https://github.com/dsifry/metaswarm/pull/116/files) and tests. Current task complexity/rubric controls mechanical/default/supercoder/debugger and fresh fixing. This is legitimate S3 decisioning, and may already be the cheaper native solution for part of the task.

Track A baseline to measure: a human reads provider status and model limits, selects their model in models.yaml, executes native generation/check, and runs the next work unit with the original review evidence. Include #116 tier behavior if merged; its own claimed use metrics are not outcomes of our S4 design.

## 3. Track B: logical first-party S4 C links

| Required C link | Reuse from Track A | Minimal missing original-native construction | Observable positive witness / falsifier |
| --- | --- | --- | --- |
| External/prospective distinction | Update skill, adapter health, model config and dated human-supplied provider facts | Versioned model capability/cost evidence contract including model ID, source, host, timestamp, expiry, task class and uncertainty | Two materially different lawful prospective routes versus stale/unknown external evidence |
| Developer-composed decision owner | Existing project role model configuration and model-backed agents | Opt-in configuration defining permitted hosts/models, evaluation criteria and explicit S4 proposer role; chooser selects keep/try/escalate, not just a static threshold | A legitimate model-backed choice between two supported options with reason, or parent escalation |
| S3 feasibility and authorization | Work-unit orchestrator, validated model resolver, protected generated files | Guarded per-work-unit proposal/accept/veto adapter with owner-set model envelope and no user-file overwrite; reject unsupported host or denied config edit | Actual chosen model is used in next eligible task only when S3 and parent scope allow |
| Future operational effect | Existing coder tasks, independent reviewer, usage helper | Attach source version and decision ID to real later task invocation, model, test and reviewer result | Next task route differs from baseline because of prior S4 choice; no effect => fails |
| Return loop / learning | Metrics agent and review reports, knowledge entries | Machine-checkable receipt containing actual later outcome; send back to the deciding S4 actor to retain/revert/escalate and record reasons | Same actor revises or retains model strategy from actual feedback; human-only report does not close S4=C |

No specific port names, test counts or new background scheduler are mandatory. Prefer a first iteration where one host has a lawful session-scoped override and real result evidence; if no such route exists, a minimal generated-artifact staging adapter may be necessary with explicit parent approval. Static documentation alone cannot substitute for an operative path.

## 4. Source-native construction order and constraints

**Observation contract:** A developer supplies a date-stamped future model change backed by a public provider source or supported local host evidence. A health probe may establish model availability; it does not establish pricing. Cost changes must have their own dated evidence, or be labelled UNKNOWN. Do not fabricate pricing or automatically scrape user/provider secrets. Model capability claims are bound to one host and version; reject stale or ambiguous signals.

**Decision composition:** Developer can install a S4 candidate policy with an explicit allowlist, maximum trial cost and eligible work types. The model-backed owner chooses, from validated options, unchanged route, staged alternate route or defer to parent, and explains forecast risk. This is not the S3 task-level tier heuristic: it looks at a future external change and propagates a recommendation into later S3.

**S3 handoff:** Existing work-unit coordinator checks task class and rights against the envelope. Only permitted per-task dispatch can trial the route. Protected user models.yaml and hand-edited generated agents must remain unchanged absent the user's exact authorization. Use generated-file hash/provenance checks, supported host model resolver and current review gates; never grant tool/credential scopes to yourself.

**Return and retention:** After the next real work unit, capture actual model identifier, test/review verdict, task class, observed usage units, failed attempts and human intervention in a local receipt linked to the S4 recommendation. Reinvoke the candidate owner to decide retain/revert/escalate based on this data. Failure, missing telemetry or untrusted facts cause a labelled UNKNOWN decision or parent escalation, never a fabricated success.

**P0:** smallest combined observation → model-backed choice → authorized S3 trial → actual later task → feedback-return path. **P1:** host support, authority, #56/#116 overlap, tests. **P2:** optional calibrated cost/extra hosts after measured benefit.

## 5. Falsifiable native acceptance — future work only

- Positive: An independently recorded provider capability shift makes two alternatives meaningfully different; owner has explicitly allowed both; S4 agent chooses the trial path based on real evidence; S3 authorizes it for a later work unit; the actual model/role is observed; independent code review returns a result; S4 receives it and produces reasoned retain/revert decision.
- Negative — rights: Owner denies the model change or models.yaml is hand-edited; no generated config overwrite, unauthorized model trial, implicit approval, or secret read.
- Negative — evidence: Provider change is expired, incompatible with host, unsupported by local health or only a guessed price; block the trial and ask for source/rights as appropriate.
- Negative — outcome: Later task fails review or lacks usage evidence; S4 records uncertainty or reversion, never claims validation or cost benefit.
- Negative — overlap: Native baseline and post-merge PR #116 solve the same supported future task at equal or lower overall cost/effort. Distinct S4 construction fails its value threshold even if technically callable.
- Alternative hypotheses: Source-mapped reuse unchanged is preferred where possible; extension is permissible only for the minimal missing decision/effect/return link. Arbitrary external skill-pack merging, broad tool policy changes or identity/mission decisions are not in scope.

**Acceptance cost comparator:** run a paired task with identical model availability, task class, host and parent permissions under manual role configuration versus bounded S4 selection; compare setup, run cost, quality review, human interventions and maintenance complexity. No numbers exist until actually measured.

## 6. Failure closure and handoff

A documentation-only proposal is not evidence of an installed autonomous S4. Current assessment S4=P is kept. If the route lacks a lawful model choice, a real future task effect or actual feedback to the same S4 owner, set a scoped NO_GO on this target; do not regrade from the absence of tests alone. A future qualified GO with NEEDS_EVIDENCE is permissible at this proposal gate but not permission to ship, publish externally or contact maintainers.

Historical comparison after independent research: [2026-11-18 cross-pack NO_GO](https://github.com/opensiro-contributions/metaswarm/blob/opensiro/meta/.opensiro/issues/cross-pack-learning-20261118/roadmap.md) evaluated original #52 external skill-pack adoption. Different unit of analysis, no contradiction or replacement. Existing owner control ACTIVE/ALLOW is only fork-local metadata permission. Third-party publication still requires separate exact prior approval.

AI assistance disclosed. No native model run, benchmark, third-party communication, product source change, or external GitHub Issue/PR has been undertaken.
