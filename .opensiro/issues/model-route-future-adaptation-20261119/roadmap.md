# metaswarm — independent six-function roadmap receipt (2026-11-19)

## Identity and pins

- Original repository: dsifry/metaswarm
- Original HEAD: 4bbb10abd301b9ec9d63371e296049cbc6043baa
- Observed at: 2026-11-19
- Accepted Index assessment: https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/assessments/me/metaswarm.md
- Accepted assessment blob SHA: 0f94c988125b87fff928898f8d849bfc21875cf7
- Accepted review ref: 4bbb10abd301b9ec9d63371e296049cbc6043baa
- Accepted reviewed at: 2026-11-18
- System in focus: One installed metaswarm project-delivery cell with role agents, host-specific model configuration, BEADS-backed orchestration, shipped skills, CLI helpers, quality gates and project knowledge; external LLM hosts, downstream project governance and third-party model providers are not owned.
- Index commit: c2e43bf4750841277b3e58d8ba80314121734764
- Accepted catalog: https://github.com/opensiro/vsm-harness-index/blob/c2e43bf4750841277b3e58d8ba80314121734764/data/catalog.psv, row 1251, harness_id metaswarm, exact original URL and review_ref matched.
- Profile / Methodology: 0.2.4 / 0.3.8
- Receipt contract: proposal-gate
- Independent original snapshot: main at 4bbb10abd301b9ec9d63371e296049cbc6043baa, identical to Index review_ref; the entire recursive tree was enumerated without truncation. No current-HEAD regrade.
- Accepted VSM vector: S1=A · S2=A · S3=A · S3*=A · S4=P · S5=—

## Rights and authority

- Original MIT license: https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/LICENSE; contributor procedure: https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/CONTRIBUTING.md. No asserted maintainer approval for this proposal.
- Verified fork: https://github.com/opensiro-contributions/metaswarm, GitHub fork of dsifry/metaswarm; opensiro/meta metadata on 2026-11-19 reports ACTIVE / ALLOW, owner event 20261119T182226Z--owner-upstream58-active. Permits internal metadata persistence; does not permit public fork Issues/PRs or original-maintainer messages without their separate exact approval.
- Authority boundary: Human project owner controls goals, budget, model allowlist, host credentials and changes to the user-authored models.yaml. A future optional adaptation actor may only select within a specifically preauthorized, time-bounded model-routing envelope. A denied permission, missing alternative or S3 veto stops the proposal.
- Contributor interest: OpenSiro is testing a bounded prospective VSM constructor, not assuming demand. Maintainer interest in lower-cost coder tiers appears in original PR #116; explicit maintainer interest in cross-task autonomous adaptation NOT_STATED.
- No new product code, external Issue/PR, original message or Index grade is authorized or created by this case.

## Existing work / overlap

- Track A SHIPPED: https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/templates/models.yaml supplies per-role Claude/Codex/Gemini defaults and escalation; https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/bin/metaswarm-agents.sh resolves roles, generates project-local Claude role files, reports missing/stale/hand-edited generation and protects them unless the user approves force. https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/tests/agents/test-adapter-models.sh exercises native model resolution and adapter health. https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/metrics-agent.md monitors agent performance, blockers, trends, knowledge base, throughput, and reports to people, without demonstrated autonomous future model-choice closure. https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/update.md checks plugin updates and guides user intervention. https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/start/SKILL.md and https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/swarm-coordinator-agent.md manage live work; https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/adversarial-reviewer.md returns independent task review evidence.
- Track A NATIVE ISSUES/PR: https://github.com/dsifry/metaswarm/issues/56 is OPEN for host-native per-role model generation in Codex, Gemini, OpenCode and Cursor. https://github.com/dsifry/metaswarm/pull/55 is MERGED and introduced role-based model configuration. https://github.com/dsifry/metaswarm/pull/116 is OPEN at b42c52cdb2885e5d2e447d1072700dccf68659ef, adding same-task mechanical/default/supercoder/debugger routing, a selection rubric, and its own tests; its actual patch was inspected. This is not shipped on original main and is not an external/future closed-loop S4 constructor.
- Native cheapest alternative: user adjusts permitted models.yaml, runs native generate/check, follows the existing update workflow, and allows the PR #116 per-task role choices if and when upstream merges it. Compare that baseline on the same future task before claiming incremental value.
- Old source question https://github.com/dsifry/metaswarm/issues/52 concerns absorption of external skill-pack practices, not this host/model adaptation object. Old OpenSiro cross-pack case is comparison material ONLY, not input to this independent P0 selection.

## Function ownership

- S1 disposition: Historical A. Installed coder, researcher and other agents perform engineering outputs via https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/start/SKILL.md and https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/coder.md. Their model selection is a support parameter, not evidence that S1 lacks an owner. DEFER.
- S2 disposition: Historical A. The model-backed swarm coordinator assigns and rebalances across worktrees and prevents writer/resource conflict in https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/swarm-coordinator-agent.md. DEFER; no extra coordination constructor demanded.
- S3 disposition: Historical A. Issue and swarm orchestration regulate current work commitments, review gates and escalation in https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/orchestrated-execution/SKILL.md; incoming review feedback changes current task actions. DEFER; open tier-routing PR #116 is an existing S3 option, not a missing S4 by itself.
- S3* disposition: Historical A. Independent fresh adversarial reviewer examines actual diffs and returns specification/rubric findings in https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/adversarial-reviewer.md. DEFER.
- S4 disposition: Historical P, a legitimate parent-governed future adaptation boundary. Self-reflection, user-managed updates, proposed cross-host configuration and metrics trends exist, but no observed source-native agent selecting a prospective model strategy, making it affect later S3 operation, then using later evidence to adjust that strategy. Qualified HYPOTHETICAL optional S4=C constructor, P0; no assertion existing S4 is broken.
- S5 disposition: Historical —. Ultimate team identity/policy/model spending rights remain with the parent user/maintainer; forcing local self-governance would cross the boundary. NO_TARGET. Evidence does not prove the project deliberately omitted every possible S5 implementation: intent UNKNOWN.

## Capability priority

- Repository-wide source map: Reviewed root README/AGENTS/CONTRIBUTING/license, install/config/plugin manifests for Claude/Codex/Gemini/OpenCode, role definitions, swarm coordination, dynamic model template/generator/adapter, commands for update/self-reflect, independent reviewer, knowledge and metrics roles, CI and tests, original issues and relevant active/merged PRs. External host intelligence, developer-only evaluation, and owner governance excluded from operational grade.
- Priority rationale: S1, S2, S3 and S3* already have adequate observed A ownership for this scoped user task, S5 is parent-controlled, and S4=P is intentionally a legitimate current mode. A bounded *optional* S4 composer can test a genuinely prospective, externally sourced model/provider change with lawful routing and later feedback. It is lower priority than simply consuming original #56 and #116 where those suffice.
- Target transition: S4=P -> S4=C
- P0: Optional developer-configurable, future-oriented model-route adaptation experiment, with evidence-stamped provider/host change signals; model-backed candidate choice within an explicit owner-approved model envelope; S3-authorized next-task routing; result/quality/usage feedback returned to the same S4 owner for retain/revise/revert/escalate.
- P1 dependencies: Recheck the exact merged status of #56 and #116 before implementing; define provenance, validity window and supported-role options; preserve human models.yaml authority and generated-file collision checks; use the shipped resolve/generate/check and available external adapter health; add a bounded S3 trial path, next-task receipt and negative permission/stale/unsupported cases; compare native baseline in a supported host with real model tasks.
- P2 optional: Only after the closed loop is proven, evaluate cost estimates or extra hosts; no cross-host feature quota and no promise of measured savings.
- Proposed C construction: A first-party opt-in adaptation skill/policy receives a dated external model-availability or provider-cost change and permitted role-model candidates. A model-backed future-facing actor chooses among maintain/try supported alternative/escalate, with reasons and evidence. Konductor-like metaswarm S3 is NOT replaced: its existing issue orchestrator checks task suitability and explicit parent envelope, commits a non-destructive per-task staging choice using a new isolated routing adapter built on the current resolver without overwriting user-authored configuration, then records the actual next work-unit, reviewer result and observed usage. The adaptation owner compares evidence and retains/reverts/asks the parent. Source adapters and new event receipts are first-party proposals, not shipped behavior.
- C sufficiency falsifier: If no prospective external signal or legal alternatives exist, if PR #116/current manual model selection already achieves the identical downstream task outcome with less effort, if S3 never applies the decision to a real later task, or if later feedback does not return to the choosing actor, this optional S4 C path is not qualified.
- Scenario basis: HYPOTHETICAL
- Proposal-stage decision: GO
- Research disposition: NEEDS_EVIDENCE
- Proposed validation: Pin host CLI/runtime and model manifests; induce a supported model becoming unavailable or an independently evidenced provider price change; compare two authorized role-model routes and the unmodified manual baseline on a later identical type of work unit. Assert real S4 choice, bounded authorization, S3 acceptance or veto, traceable next-task model invocation and independent review results, later actor feedback, and explicit stale/denied/offline/hand-edited-file negatives.
- Validation state: NOT_RUN
- Proposal falsifier: Any inability to form two valid authorized alternatives, an unauthorized configuration edit, absent future-oriented distinction, absent later-return feedback, or parity with simpler native routing that defeats incremental usefulness requires new scoped NO_GO.
- Research interpretation: GO qualifies an untested complete *proposal* as a falsifiable construction hypothesis; it is NOT proof of implemented C, maintained product quality, accepted Index grade or economic improvement.

## Parallel contribution-on-top review

- Evaluation object: Prospective cross-task model/provider adaptation for a project-delivery cell (S4=P -> optional S4=C), NOT review-gate quality, task-tier routing alone, arbitrary agent improvements or skill-pack merging.
- Existing-work overlap: MERGED #55 config generation; OPEN #56 host-native per-role model files; OPEN #116 coder-tier choice from current task difficulty with rubric; built-in manual role map and user update flow. Each is reusable, none is credited as already shipped S4 prospective choice-and-later-feedback on original main.
- Our on-top contribution: A small developer-composable prospective signal + authorized option set + versioned proposed route, a guarded S3 application of one candidate for one later task, and an evidence return/re-evaluation receipt; use native role resolver and agents instead of duplicating their functions.
- Incremental benefit: Potentially reduce repeated manual choice when model availability/cost changes across tasks, ONLY IF paired tests beat the existing manual-plus-#116 baseline; unmeasured and no maintainer demand asserted.
- Decision scope: Source-native proposal only, independent of original #52 cross-pack case; no original Issue, fork GitHub Issue/PR or code change without exact later publication/implementation authority.

## Implementation options

- Reuse unchanged: Source-shipped role configuration, current model resolver/check, metrics and independent review as evidence producers. Use manual baseline as the default when S4 proposal fails authority/utility.
- Integrate/extend: Add an opt-in small future-observation and versioned S4 recommendation format and a guarded staged next-task role selection mechanism which does not mutate the parent-owned models.yaml; return live task/reviewer/usage receipts to S4.
- Adjacent capability: Additional third-party host support or automatic marketplace upgrade is separate, speculative and not needed to demonstrate this S4 C constructor. No autonomous install/permissions/model account changes.
- Distinctness: Existing per-task tier heuristics are S3 current execution; the proposed alternative decides how an allowed strategy should change for later tasks in response to dated external change, and re-evaluates that strategy based on real later operations.

## Specification and domain alternatives

- No discovered Profile/Skills inconsistency is asserted. The accepted S4=P classification is preserved without upgrading to C in the Index.
- Original-native user request is represented by original #56 and PR #116. No duplicate external Issue is appropriate now; reassess any proposal after their resolution. Third-party maintainer interest for this specific proposal NOT_STATED.
- A standalone OpenSiro fork-only experiment might test the hypothesis, but is not an approved product change or a current contribution record.

## Cost experiment

- Cost status: NOT_MEASURED
- Matched future experiment: Same pinned host and task class, manual models.yaml/role routing versus a lawful staged adaptation path; count agent usage, rework/review failures, human confirmations, engineering and integration effort, and maintenance. Source PR #116 reports its own motivation; that is not evidence of savings for this S4 hypothesis.

## Delivery and publication

- Result: PLAN_ONLY
- External issue: DRAFT — NOT PUBLISHED
- Case: .opensiro/issues/model-route-future-adaptation-20261119/ on opensiro/meta in verified opensiro-contributions/metaswarm.
- Human document: [issue.md](issue.md); AI constructor: [constructor-sufficiency.md](constructor-sufficiency.md); case index [README.md](README.md).
- Historical comparison (performed only after independent selection): Existing [cross-pack learning NO_GO](https://github.com/opensiro-contributions/metaswarm/blob/opensiro/meta/.opensiro/issues/cross-pack-learning-20261118/roadmap.md) rejects unscoped skill-pack absorption from original #52. This independent S4 host/model route GO is a different target with a candidate task and lawful ports. No historical verdict overwritten or converted.
- Tests: Documentation structural validator to be run on all three case files before persistence; future native model/run tests NOT_RUN; value/ROI NOT_MEASURED.
- Publication: Internal attributed fork metadata record allowed by live ACTIVE / ALLOW; public fork Issue/PR, original Issue/PR/comment, product changes, and assessment regrade NOT_PUBLISHED / NOT_AUTHORIZED by this roadmap.
- Next permitted action: review design and possibly seek separately approved, source-native experiment after upstream #56/#116 update; stop if approval, host evidence, or non-mutating route cannot be established.
