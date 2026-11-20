# AI/developer constructor sufficiency — metaswarm Wave 4 cross-pack adaptation

**Target transition:** S4=P -> S4=C
**Proposal-stage decision:** GO
**Research disposition:** NEEDS_EVIDENCE

[issue.md](issue.md) is the Human-facing six-function table and unpublished issue draft. [roadmap.md](roadmap.md) owns the current canonical decision and pins. Original 4bbb10abd301b9ec9d63371e296049cbc6043baa and accepted Index 308548ec89534590f948bc75dd61887e992a3756 / blob 0f94c988125b87fff928898f8d849bfc21875cf7; v0.18.0 @ 28ea2cce06b517bc4550dceddb00210b1e0dc85c. These are not new Index grades.

## Boundary and decision-right mapping

Function S4: sense external changes/experience beyond this project, independently choose a forward-looking adaptation, affect subsequent local operations, and receive feedback to retain/revise. Proposed first-party owner is an installed metaswarm cross-pack adaptation curator with model judgment governed by **authored first-party instructions**, not an assumed intelligence feature of host Claude/Gemini/Codex. Opt-in policy is set by project human and only authorizes local reversible candidate knowledge edits. Parent retains broader S5 authorization/merges and publisher rights.

Minimum source-native path: https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/issue-orchestrator.md phase-9 curation entry, https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/agents/knowledge-curator-agent.md source/fact curation, https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/self-reflect.md source filtering, https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/prime.md knowledge-to-task consumption, https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/knowledge/README.md JSONL provenance/usage fields. Local source allowlist and per-project opt-in are NEW proposed bounded contracts, not claimed shipped.

### Minimal P0: four linked, owned functions

1. **Sense** — read only licensed allowlisted external pack/review/release documentation and observed later task results with immutable source URL, version and project context. Treat external instructions as data, never execute or auto-install them.
2. **Decide** — prospective curator independently chooses ADOPT_TRIAL / HOLD / REJECT / RETIRE based on scoped task applicability, conflicts, allowed operation, confidence and deprecation. Human need not approve every low-risk candidate; unknown authority -> HOLD with zero mutations.
3. **Effect** — write an append-only/reversible trial entry to project-local .beads/knowledge facts, versioned with origin, target path, expiry, decision and fact ID. /prime reads only authorized scoped trials and affects a future task plan; high-risk code/skills, external PRs, protected policy and source scope remain human-owned.
4. **Return** — later review/corrections/PR results reference the fact ID; independent curator confirms, withdraws or retires before further prime. Write an attributable decision and feedback record; if no after-run evidence, remain trial/unknown, never assert improved quality.

This is a coherent candidate autonomous S4 decision/effect/return constructor, but remains HYPOTHETICAL and NOT_RUN. It is **not** a generic knowledge crawler, storage layer, S3 post-hoc bug fix, or S5 autonomous rulemaking.

## Track A original overlap and non-equivalence

Native https://github.com/dsifry/metaswarm/blob/4bbb10abd301b9ec9d63371e296049cbc6043baa/commands/self-reflect.md explicitly asks a human to select candidate learnings and resolve conflicts. Native /prime is a *read/filter* path, not the cross-pack forward-looking chooser. Original [#52](https://github.com/dsifry/metaswarm/issues/52) describes a possible cross-pack learning use case. Open [#37](https://github.com/dsifry/metaswarm/pull/37) offers shared cross-project memory and handoffs; even if merged, storage alone lacks the independent adoption/retirement decision and downstream evidence loop. Open [#36](https://github.com/dsifry/metaswarm/pull/36) preserves session state; open [#116](https://github.com/dsifry/metaswarm/pull/116) coder-tier policy. None counted as shipped S4 C closure at original HEAD; merged [#104](https://github.com/dsifry/metaswarm/pull/104) is a user Clarify check. Existing manual editing may be the best **product** solution and has unknown cost; that cannot by itself establish existing C closure.

## Negative constructors

- Search/SQLite/FTS-only knowledge sharing: no decision or returned effect; **NOT C**.
- Auto-merge any other pack into source or run imported instructions: unsafe external rights/authority, unbounded side effects; **REJECT**.
- Every candidate selected only by human: valid P/manual workflow but autonomous S4 decision ownership not constructed.
- Pure LLM recommendation without KB edit and later return: **NOT C**.

## Native acceptance/ falsification gates

Positive fixture: licensed allowlisted source version; target task; agent chooses one permitted trial, rejects one conflicted practice and holds one unknown license; only trial enters project KB; next task /prime demonstrably consumes fact; later review triggers independently attributable keep/retire; denied source or permissions cause no mutation. Compare a human self-reflect/prime run for actual value and cost **after** the architectural test.

Failure: no verifiable source rights, parent-owned policy decision masquerading as model autonomy, no downstream change, missing receipt/fact-ID feedback, or first-party shipped same-scope C loop. Product value failure does not retroactively make a structurally coherent C path impossible. No native tests executed in this research.

## Comparison and safety

Independent six-function first pass completed before prior OpenSiro case was read. Old [same-case NO_GO](https://github.com/opensiro-contributions/metaswarm/blob/560d659b622edd4effaadcf84f6b513c289a1423/.opensiro/issues/cross-pack-learning-20261118/roadmap.md) relied on no grounded incremental demand, product value and insufficient example. Under published v0.18.0 neutrality this new scoped complete construction earns **GO / NEEDS_EVIDENCE** (NOT_RUN). Historical evidence survives immutable Git, not rewritten as a 2026-11-19 GO. Parent original repo and any public fork Issue or PR not touched. AI-assisted plan-only research; tested code none, cost unmeasured.
