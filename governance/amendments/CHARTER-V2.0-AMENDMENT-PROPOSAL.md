# Charter v2.0 Amendment Proposal

Status: proposal only  
Target: WEAI Charter v2.0  
Repository: weai-charter  
Path: governance/amendments/CHARTER-V2.0-AMENDMENT-PROPOSAL.md  
Adoption effect: none until merged through the amendment protocol  
Supersedes: none by this proposal alone  

---

## 0. Non-Adoption Statement

This file is an amendment proposal only.

It does not:

- amend WEAI-Charter-v1.0;
- create WEAI-Charter-v2.0;
- supersede any admitted Charter version;
- admit any new governance component;
- authorize execution;
- activate Runtime;
- issue grants;
- issue API tokens;
- authorize billing, settlement, or production capability use.

No local file, draft, model output, chat message, or unmerged branch has governance authority.

A Charter v2.0 version becomes admitted only if a separate versioned Charter file is created and adopted through the amendment protocol.

---

## 1. Proposal Purpose

This proposal requests a Charter v2.0 amendment path for clarifying the full WEAI / weai.solutions ecosystem architecture.

The purpose is to move from a repository-local governance model toward an ecosystem-level constitutional model that can support:

- capability factory networks;
- AI service platform networks;
- public API OS access;
- runtime contract layers;
- token, billing, settlement, and audit flows;
- external model and agent adapter boundaries;
- non-overlap rules across all WEAI repositories.

This proposal exists because the current system has reached a point where repo-by-repo governance is insufficient to prevent boundary drift, duplicate authority, and over-development in the wrong repository.

---

## 2. Proposed Executive Positioning

The proposed Charter v2.0 positioning is:

```text
WEAI / weai.solutions
= AGI-era Fair, Trusted, Auditable Solutions OS
= open to all stakeholders, including humans, enterprises, institutions, and AI agents
= governed capability infrastructure for transparent, compliant, accountable value exchange
```

Chinese business meaning, not normative Charter text:

```text
WEAI / weai.solutions
= 面向 AGI 时代的公平、公信、公正、可治理、可审计、可合规的 Solutions OS
= 对所有利益相关方开放，包括人类、企业、机构与 AI Agents
= 用治理稳定性支撑能力调用、产业交易与价值交换的新型基础设施
```

The proposed Charter v2.0 should define weai.solutions as the API OS entry and commercial access surface for the WEAI ecosystem, not as a single product, not as a capability factory, and not as a service platform.

---

## 3. Current Charter v1.0 Baseline

The active Charter currently recognizes a narrower governance model.

This proposal does not reinterpret Charter v1.0. It records that Charter v2.0 may need to clarify:

- the constitutional position of WEAI / weai.solutions;
- the relationship between Charter, Canon, Kernel, Runtime, and Registry;
- whether additional ecosystem components should be admitted as named governance components;
- whether public API OS, capability factories, AI service platforms, and commercial ledgers require explicit Charter placement.

Until Charter v2.0 is adopted, Charter v1.0 remains authoritative.

---

## 4. Structural Diff Summary

Proposed Charter v2.0 would move from:

```text
Charter
Canon
Kernel
Runtime
Registry
```

Toward an ecosystem-level model such as:

```text
Charter
  -> Canon
  -> Kernel
  -> Harness
  -> Execution Engine
  -> Runtime Public Contract Layer
  -> Registry
  -> Capability Factory Network
  -> AI Service Platform Network
  -> API OS / weai.solutions
  -> Commercial Ledger / Token / Billing / Settlement / Audit
```

This proposal does not admit this structure. It only identifies the structural question that Charter v2.0 must decide.

---

## 5. Core Question for Charter v2.0

Charter v2.0 must answer:

```text
What is WEAI / weai.solutions in the AGI-era infrastructure stack?
```

Candidate answer:

```text
weai.solutions is the governed API OS that connects capability producers,
capability consumers, service platforms, governance authority, validation,
execution, registry, runtime contracts, token access, billing, settlement,
and audit into one accountable transaction path.
```

The Charter v2.0 amendment should decide whether this answer becomes admitted constitutional positioning.

---

## 6. Proposed Ecosystem Component Matrix

| Layer | Candidate Component | Candidate Role | Not Allowed |
|---|---|---|---|
| Constitutional | Charter | Sovereignty, authority hierarchy, admitted layer model | Runtime, billing, service logic |
| Normative | Canon | Normative execution and ledger principles | Implementation code, commercial routing |
| Governance | Kernel | Authority semantics, manifest admission, grants | Runtime execution, billing |
| Validation | Harness | Invocation boundary validation | Business execution, billing, capability production |
| Internal Execution | Execution Engine | Internal admitted execution carrier | Public contract trust, self-authority |
| Public Contract | Runtime public repo | External API/runtime contract standard | Private execution logic, unauthorized billing |
| Capability Production | Capability factories | Capability modules and manifests | Grant authority, token issuance, direct settlement |
| Registry | weai-registry | Capability manifest and metadata registry | Execution, grants, billing |
| API OS | weai.solutions | API gateway, token access, capability marketplace, integration surface | Constitutional authority, hidden runtime |
| Service Platforms | TaxEnd.ai / DryCleanOne / others | Vertical AI service delivery and transaction scenarios | Self-authority, unmanaged execution |
| Commercial Ledger | billing/token/settlement/audit | Usage accounting, transaction closure, revenue record | Capability definition, governance authority |

This matrix is proposed for review only. It has no authority until incorporated into an adopted Charter amendment.

---

## 7. Capability Factory Position

Capability factories produce capability modules.

They may:

- define capability behavior;
- prepare manifests;
- declare maturity level;
- define input and output behavior;
- prepare service packaging;
- generate observable outputs.

They must not:

- grant authority;
- execute production transactions directly;
- issue API tokens;
- settle billing;
- override Kernel;
- bypass Harness;
- self-register as admitted ecosystem authority.

Capability factories are producers of capability supply. They are not the transaction authority.

---

## 8. AI Service Platform Position

AI service platforms consume capabilities and create business transaction scenarios.

Examples may include:

- TaxEnd.ai;
- DryCleanOne Admin;
- future vertical AI service platforms.

They may:

- serve end users;
- initiate platform requests;
- call admitted capabilities through the governed path;
- participate in transaction closure.

They must not:

- define system authority;
- bypass Registry, Kernel, Harness, Runtime, or billing controls;
- self-admit capabilities;
- self-issue tokens;
- self-settle usage outside the admitted commercial ledger.

Service platforms are demand-side transaction surfaces. They are not the governance root.

---

## 9. weai.solutions API OS Position

weai.solutions should be evaluated as the ecosystem entry and API OS layer.

Candidate responsibilities:

- developer access surface;
- API key and tenant token access;
- capability marketplace / directory surface;
- public integration surface;
- commercial routing surface;
- platform account layer;
- documentation and external onboarding surface.

weai.solutions should not be treated as:

- a capability factory;
- a service platform;
- a governance root;
- a hidden runtime implementation;
- a billing ledger by itself;
- a replacement for Kernel, Harness, Runtime, or Registry.

---

## 10. Runtime Public Repo Position

Runtime public repo should be preserved as a public trust contract layer.

Candidate role:

```text
weai-runtime = public runtime contract / API standard layer
weai-execution-engine = internal execution carrier
weai.solutions = commercial API OS gateway / integration surface
```

Runtime public repo should not expose private execution implementation.

Runtime should define public contract expectations, not become a hidden execution engine.

---

## 11. Execution Engine Position

Execution Engine is the internal execution carrier.

It may:

- carry admitted internal execution;
- emit internal execution events;
- consume validated authority and contract paths.

It must not:

- become the public API standard layer;
- self-issue authority;
- self-register capabilities;
- become billing or settlement authority;
- override Charter, Canon, Kernel, Registry, or Runtime public contracts.

---

## 12. Kernel and Harness Position

Kernel and Harness should remain distinct.

Candidate distinction:

```text
Kernel = authority semantics and admission logic
Harness = invocation boundary validation and non-bypassable execution gate
```

Kernel should not perform runtime execution.

Harness should not define governance authority.

Harness closure already established that Harness is bounded engineering and not a Runtime, Capability, or Stage 5 expansion surface.

---

## 13. Registry Position

Registry should remain declarative.

It may:

- store capability manifests;
- store metadata;
- expose registry records;
- support discovery and validation.

It must not:

- issue grants;
- execute capabilities;
- create authority by implication;
- settle billing;
- override Kernel or Charter.

---

## 14. Token, Billing, Settlement, and Audit Position

Token and billing logic should not live inside capability factories, Kernel, or Harness.

Candidate placement:

```text
weai.solutions
= API access surface / tenant token request / commercial account surface

runtime + billing + settlement layer
= metering truth / usage accounting / billing truth / settlement truth

Kernel
= determines whether authority path exists

Harness
= validates whether invocation is admissible

Execution Engine
= emits executable/internal runtime event after validation
```

Candidate transaction path:

```text
API key / tenant token
-> request envelope
-> capability id
-> scope
-> model/service usage
-> execution event
-> metering event
-> billing event
-> settlement/audit event
```

This proposal does not create those systems. It identifies where Charter v2.0 should place them.

---

## 15. External Model and Agent Adapter Strategy

External model and agent providers may be integrated through adapters.

Examples:

- OpenAI models;
- Anthropic models;
- other LLM providers;
- third-party agent frameworks;
- enterprise model gateways.

Adapter principles:

- external models are suppliers, not sovereignty authorities;
- adapters must not bypass Registry, Kernel, Harness, Runtime, or billing controls;
- provider-specific logic must remain replaceable;
- model invocation must remain auditable;
- commercial attribution, cost, latency, and usage must be measurable.

weai.solutions may expose a stable API OS while internal adapters translate provider-specific model and agent calls.

---

## 16. Non-Overlap Rules

Charter v2.0 should define non-overlap rules to prevent repo drift.

Candidate rules:

- Charter defines authority, not implementation.
- Canon defines normative behavior, not product features.
- Kernel defines admission authority, not runtime execution.
- Harness validates invocation boundaries, not business workflows.
- Execution Engine carries internal execution, not public trust contracts.
- Runtime public repo defines public contract standards, not private execution logic.
- Registry stores declarative manifests, not grants or settlements.
- Capability factories produce capabilities, not platform authority.
- Service platforms consume capabilities, not system sovereignty.
- weai.solutions exposes API OS and commercial access, not hidden governance.
- Billing/token/settlement/audit records usage and revenue, not capability semantics.

---

## 17. Boundary Impact Review

Potential affected admitted or candidate boundaries:

- Charter;
- Canon;
- Kernel;
- Runtime;
- Registry;
- platform implementations;
- skill execution frameworks;
- future Harness boundary;
- future Execution Engine boundary;
- future API OS boundary;
- future capability factory boundary;
- future AI service platform boundary;
- future token/billing/settlement/audit boundary.

This proposal does not make these candidate boundaries admitted. It identifies them for Charter v2.0 review.

---

## 18. Lower-Layer Impact Review

If Charter v2.0 is adopted, possible downstream follow-up records may be required in:

- weai-canon;
- weai-kernel;
- weai-harness;
- weai-execution-engine;
- weai-runtime;
- weai-registry;
- capability-factory;
- service platform repos;
- commercial ledger / token / billing / settlement repos, if created.

This proposal does not edit those repositories.

No downstream repository is modified by this proposal.

---

## 19. Sovereignty Compliance Verification

This proposal complies with the current Charter amendment protocol because:

1. It is a proposal only.
2. It does not mutate Charter v1.0.
3. It does not create Charter v2.0.
4. It does not admit any new layer.
5. It does not create runtime authority.
6. It does not issue grants.
7. It does not bypass the amendment protocol.
8. It records structural questions for future governance decision.

---

## 20. Required Decision

The governance decision required after review is:

```text
Should WEAI proceed to draft a separate WEAI-Charter-v2.0.md file based on this amendment proposal?
```

Possible decisions:

- Adopt proposal and authorize drafting Charter v2.0.
- Revise proposal.
- Reject proposal.
- Split proposal into Charter and Canon workstreams.
- Defer until additional repository boundary audits are complete.

This proposal does not decide the answer.

---

## 21. Final Proposal Statement

This proposal records that WEAI / weai.solutions may require Charter v2.0 positioning as an AGI-era Fair, Trusted, Auditable Solutions OS.

It requests governance review of the ecosystem architecture, repository boundaries, API OS positioning, capability factory role, service platform role, runtime contract model, external model adapter strategy, and token/billing/settlement/audit placement.

Until adopted through the amendment protocol, this file has no governance authority beyond proposal status.
