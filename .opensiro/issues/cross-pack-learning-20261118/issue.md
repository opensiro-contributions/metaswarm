# metaswarm — Wave 4 source-native cross-pack learning proposal (unpublished)

**PLAN_ONLY · proposal-stage GO · research NEEDS_EVIDENCE · DRAFT — NOT PUBLISHED**

**One-sentence proposal:** Offer an opt-in, source-allowlisted prospective learning agent that autonomously tries, observes and retracts reusable practices from other skill packs through metaswarm's existing project knowledge and priming path; this is a design to test, not a request to ship.

**Target transition:** S4=P -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

**Canonical evidence:** [roadmap.md](roadmap.md). **Technical constructor and falsifier:** [constructor-sufficiency.md](constructor-sufficiency.md). Existing stable case in opensiro-contributions/metaswarm, opensiro/meta. Original and Index source pinned, no grade change or product implementation.

## Scope and accepted historical assessment

Original dsifry/metaswarm @ 4bbb10abd301b9ec9d63371e296049cbc6043baa; accepted Index 308548ec89534590f948bc75dd61887e992a3756 included; historical vector S1=A · S2=A · S3=A · S3*=A · S4=P · S5=—. Post-release v0.18.0 neutrality rerun 2026-11-20; all decisions are proposals, not shipped grades, product-adoption advice, or verified tests. [Accepted assessment](https://github.com/opensiro/vsm-harness-index/blob/308548ec89534590f948bc75dd61887e992a3756/assessments/me/metaswarm.md), blob 0f94c988125b87fff928898f8d849bfc21875cf7, Profile 0.2.4 / Methodology 0.3.8. The grading describes decision ownership, not quality or a mandatory requirement that all functions be C. The parent coding host, original product maintainer and human project owner retain their own separate authority.

| Function / plain-language role | Historical state | Source-native path and scope of new proposal |
| --- | --- | --- |
| **S1 · Operations** | A | [Orchestrated worker execution](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/skills/orchestrated-execution/SKILL.md) implements, tests and corrects work units; no new function owner proposed |
| **S2 · Coordination** | A | [Swarm coordinator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/swarm-coordinator-agent.md) manages concurrent worktrees and interference; no extra C target |
| **S3 · Current control** | A | [Issue orchestrator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/issue-orchestrator.md) allocates tasks, checks and rebalances current execution; human merge is still reserved |
| **S3* · Independent audit** | A | [Adversarial reviewer](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/adversarial-reviewer.md) independently audits and returns findings to the work loop |
| **S4 · Future adaptation** | P | [Self-reflect](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/self-reflect.md), [curator](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/knowledge-curator-agent.md) and [prime](https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/prime.md) already handle retrospective local learning. Proposed S4=C adds a separate authorized prospective external-pack adopt/trial/retire decision and later feedback |
| **S5 · Identity and policy** | — | Human owner controls source licenses, allowed imports, high-risk changes, strategy and merge; no S5 handoff |

## Practical proposed task

On a project that opts in to a specific external source/pack, metaswarm may ingest an attributed practice or review finding, decide trial/hold/reject/retire under local project policy, place a reversible trial fact in project BEADS knowledge, load it via /prime for the next related authorized issue, then read later review and success/failure evidence to keep or roll back. No imported instructions are run as commands, no original repository or third-party publisher is contacted, and no external rule becomes universally authoritative.

Source basis: [original issue #52](https://github.com/dsifry/metaswarm/issues/52) OPEN; [original PR #37](https://github.com/dsifry/metaswarm/pull/37) OPEN shared-memory storage, not shipped; [PR #36](https://github.com/dsifry/metaswarm/pull/36) OPEN compaction memory; [PR #116](https://github.com/dsifry/metaswarm/pull/116) OPEN coder tiers. Shipped reflection/prime is the minimal manual comparison, not an automatic veto on structural constructibility.

## Track A ↔ Track B and priorities

**A:** continue human choice through /self-reflect and /prime; optionally use native #37 when it merges. **B / P0:** first-party opt-in cross-pack adaptation actor with an independently owned, rights-bounded decision, a local reversible effect and an observed after-task return. **B alternatives rejected as C:** search-only/shared-memory store, blind rule merge without licenses and feedback, static role that still asks humans to choose every candidate.

**P1 (evidence):** demonstrate source license/permissions, portable invocation, project opt-in, no KB corruption, effect on next task, later feedback and rollback; run matched native/manual A/B tests. **P2:** none. A failed experiment or enough native support can make the feature undesirable; that is a maintainer's product decision.

**Scoped verdict:** architectural **GO / NEEDS_EVIDENCE** for S4=P -> S4=C, not a deployed S4=C grade. **Falsifier:** a shipped same-scope native independent S4 adopt/trial/retire-and-return owner, no lawful scoped project decision/KB write, or no reachable next-task effect and subsequent evidence. A mere cost or preference comparison is not equivalent C function closure.

## Historical and publication boundary

Independent review was written before reading old case. The [2026-11-19 NO_GO receipt](https://github.com/opensiro-contributions/metaswarm/blob/560d659b622edd4effaadcf84f6b513c289a1423/.opensiro/issues/cross-pack-learning-20261118/roadmap.md) remains historically attributable and is superseded **only** as the present proposal-stage evaluation under v0.18 neutrality: old NO_GO -> proposed GO. Native tests NOT_RUN; costs NOT_MEASURED; no third-party GitHub Issue, fork public Issue, original PR/comment or implementation. This is an OpenSiro metadata draft only.
