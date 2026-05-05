# Charter Amendment Protocol

**Record type:** Governance procedure  
**Status:** v1.0  
**Bootstrap status:** This protocol is bootstrapped under founder authority due to the absence of a pre-existing amendment protocol referenced by the Charter repository governance surface. From this admission forward, future amendments to this protocol itself follow the major amendment procedure defined here.  
**Repository:** `weai-charter`  
**Path:** `governance/amendment-protocol.md`  
**Authority effect:** Procedural only  
**Execution effect:** None  
**Grant effect:** None  
**Runtime effect:** None  
**Registry effect:** None  
**Billing effect:** None  

---

## 0. Purpose

This protocol defines the required procedure for proposing, reviewing, adopting, superseding, or rejecting amendments to the WEAI Charter.

It exists to make Charter evolution explicit, reviewable, versioned, and non-retroactive.

This protocol does not itself amend the Charter.

It supplies the missing procedural mechanism referenced by the current Charter repository governance surface.

---

## 1. Scope

This protocol applies to:

- any proposed new Charter version;
- any proposed major revision to the Charter;
- any proposed amendment that changes Charter-level sovereignty, authority, hierarchy, repository boundaries, governance order, or amendment rules;
- any proposal to supersede, archive, or replace a prior Charter version;
- any proposal that affects the relationship between governance components admitted by the currently active Charter. Future governance components may be brought into scope only through this protocol's amendment procedure.

This protocol does not apply to:

- typo-only documentation fixes that do not alter meaning;
- formatting changes that do not alter meaning;
- repository hygiene records that do not amend Charter authority;
- Canon-level normative behavior rules unless they require Charter-level authority changes;
- implementation changes in any repository unless they require Charter-level authority changes.

---

## 2. Non-Authorization Rule

A proposed amendment is not effective merely because it is drafted, discussed, committed, or opened as a pull request.

Until an amendment is explicitly adopted under this protocol:

- the current admitted Charter remains authoritative;
- the proposed text has no authority effect;
- no lower layer may rely on the proposal as admitted governance;
- no repository may treat the proposal as permission to mutate its authority boundary;
- no execution, runtime, registry, billing, settlement, or capability admission authority is created.

Silence remains non-authorization.  
Ambiguity remains deny.

---

## 3. Immutability Rule

Admitted Charter versions are immutable historical records.

An admitted Charter version MUST NOT be silently rewritten.

A later Charter version may supersede an earlier version only through an explicit amendment record and a new versioned Charter file.

Required pattern:

```text
WEAI-Charter-v1.0.md  -> retained as historical baseline
WEAI-Charter-v2.0.md  -> new admitted version only after protocol completion
```

Not allowed:

```text
overwrite v1.0 in place
delete prior admitted Charter versions
retroactively edit prior Charter meaning
treat a draft as admitted Charter
```

---

## 4. Amendment Classes

### 4.1 Editorial Change

An editorial change corrects non-semantic errors.

Examples:

- spelling correction;
- formatting correction;
- broken link correction;
- non-semantic file reference correction.

Editorial changes may be handled by ordinary documentation PR if the PR explicitly states that no Charter meaning changes.

### 4.2 Minor Amendment

A minor amendment clarifies existing Charter meaning without changing authority structure.

Examples:

- terminology clarification;
- cross-reference correction with semantic relevance;
- non-substantive explanatory note;
- clarification of existing admitted components without altering their authority.

Minor amendments may be handled by amendment PR if the proposal explicitly states that no Charter authority, hierarchy, or boundary changes.

A change is Minor only if it can be shown that no admitted component's authority effect, execution effect, or boundary scope changes. If any doubt exists, the change is Major.

### 4.3 Major Amendment

A major amendment changes Charter meaning, authority hierarchy, repository role, governance order, layer structure, sovereignty semantics, or admitted system boundary.

Examples:

- introducing or removing a governance layer;
- changing the hierarchy among admitted layers;
- redefining the role of any admitted governance component;
- changing amendment procedure;
- changing source-of-truth rules;
- changing authority, admission, execution, registry, runtime, or commercial boundary semantics;
- changing what may count as an admitted governance record.

Major amendments require the full amendment process in this protocol.

### 4.4 Emergency Amendment

An emergency amendment addresses an immediate governance defect that blocks safe operation or creates contradictory authority.

Emergency amendments still require:

- explicit amendment classification;
- written rationale;
- versioned record;
- review;
- final decision;
- no retroactive mutation.

Emergency status reduces delay; it does not remove review.

---

## 5. Required Amendment Artifacts

Every Charter amendment requires review artifacts appropriate to its class.

Major amendments require all of the following artifacts.
Minor and emergency amendments require the same artifacts unless the proposal explicitly states why a specific artifact is not applicable.
Editorial changes require an explicit no-semantic-change statement.

1. Amendment proposal.
2. Structural diff summary.
3. Sovereignty compliance verification.
4. Boundary impact review.
5. Lower-layer impact review.
6. Final governance decision.
7. New versioned Charter file, if adopted.

Recommended paths:

```text
governance/amendments/CHARTER-V<target>-AMENDMENT-PROPOSAL.md
WEAI-Charter-v<target>.md
```

Example:

```text
governance/amendments/CHARTER-V2.0-AMENDMENT-PROPOSAL.md
WEAI-Charter-v2.0.md
```

---

## 6. Amendment Proposal Requirements

An amendment proposal MUST include:

- amendment title;
- target Charter version;
- amendment class;
- motivation;
- problem statement;
- affected Charter sections;
- affected admitted governance components;
- authority effects;
- non-effects;
- compatibility statement;
- supersession statement;
- migration plan;
- explicit adoption rule;
- rollback or rejection consequence;
- reviewer checklist.

The proposal MUST state whether it is:

```text
non-authorizing draft
amendment candidate
adopted amendment
rejected amendment
superseded amendment
```

Only `adopted amendment` has authority effect.

---

## 7. Structural Diff Requirement

Every major amendment MUST include a structural diff summary.

The structural diff must identify:

- new layers added;
- layers removed;
- layers renamed;
- boundary changes;
- authority changes;
- repository responsibility changes;
- normative vs informative sections;
- parts intentionally deferred.

The structural diff must not hide governance impact inside prose.

Required table format:

| Area | Prior Charter | Proposed Charter | Effect |
|---|---|---|---|
| Example | existing definition | proposed definition | description of effect |

---

## 8. Sovereignty Compliance Verification

Every major amendment MUST verify that the proposal preserves Charter sovereignty.

The verification must answer:

1. Does the amendment preserve Charter as the highest admitted governance authority?
2. Does the amendment avoid retroactive mutation of prior admitted versions?
3. Does the amendment preserve top-down authority discipline?
4. Does the amendment prevent lower layers from overriding Charter?
5. Does the amendment avoid creating hidden execution, runtime, registry, token, billing, or settlement authority?
6. Does the amendment preserve non-authorization by silence?
7. Does the amendment define whether each new section is normative or informative?
8. Does the amendment identify downstream repositories affected by the change?

If any answer is unclear, the amendment MUST NOT be adopted.

---

## 9. Boundary Impact Review

Every major amendment MUST include a boundary impact review.

For each amendment proposal, the boundary impact review must identify which admitted governance boundaries are affected.

Admitted boundaries are those recognized by the active Charter.

Future amendments that introduce new boundaries MUST include those boundaries in their own boundary impact review as part of the same amendment proposal that admits them.

For each affected boundary, the proposal must state:

```text
No change
Clarification only
Authority change
New boundary introduced
Boundary deprecated
Deferred
```

This protocol does not pre-admit future boundaries by listing them before Charter admission.

---

## 10. Lower-Layer Impact Review

A Charter amendment MUST NOT silently mutate lower repositories.

If a Charter amendment requires downstream changes, those changes must be listed as separate downstream work items.

Examples:

- Canon alignment proposal;
- Kernel alignment record;
- Runtime public contract alignment;
- Registry manifest boundary cleanup;
- repository-local status or README update;
- other downstream records required by the adopted Charter amendment.

A Charter amendment may authorize a future downstream review path, but it does not automatically edit downstream repositories.

---

## 11. Canon Relationship

Canon is below Charter.

Canon may define normative execution, ledger, registry, or boundary behavior only within the authority allowed by Charter.

If a proposed Canon change requires a Charter-level authority change, Charter amendment must occur first.

Canon must not:

- override Charter;
- redefine Charter sovereignty;
- admit new top-level layers without Charter authority;
- use Canon text to mutate Charter meaning;
- create hidden authority through behavior rules.

---

## 12. Kernel Relationship

Kernel is below Charter and Canon.

Kernel may implement or record authority semantics only within admitted Charter and Canon boundaries.

Kernel must not:

- create Charter authority;
- admit capability execution authority outside the admitted governance path;
- treat a draft Charter or draft Canon as active authority;
- use implementation state to override Charter or Canon.

---

## 13. Runtime Relationship

Runtime is below Charter, Canon, and Kernel.

Runtime may implement commercial and policy enforcement only within admitted Charter and Canon boundaries.

Runtime must not be activated by implication.

A Charter amendment may revise Runtime's role, but Runtime activation requires separate admitted downstream work.

---

## 14. Registry Relationship

Registry is below Charter, Canon, Kernel, and Runtime.

Registry is declarative within admitted Charter authority.

Registry must not:

- issue grants;
- create execution authority by implication;
- self-admit capabilities;
- override Kernel;
- become billing or settlement authority by implication.

---

## 15. Future Component Relationships

This protocol does not predefine relationships for components not currently admitted by the active Charter.

Future amendments that add new governance components must define their relationship to existing admitted layers as part of the same amendment proposal that admits them.

A Charter amendment that admits a new layer or component MUST include in its proposal:

- the new component's name;
- its position in the dependency hierarchy;
- its authority effect, if any;
- its execution effect, if any;
- its registry effect, if any;
- its runtime effect, if any;
- its billing or settlement effect, if any;
- its forbidden actions;
- its lower-layer impact;
- its migration or non-migration plan.

This amendment protocol itself does not predefine those relationships, because doing so would pre-admit components that have not yet passed through the amendment procedure.

---

## 16. Adoption Procedure

An amendment is adopted only when the adoption requirements for its class are satisfied and the adopting PR is merged into main.

Editorial changes are adopted when the PR explicitly states no semantic change and is merged.

Minor amendments are adopted when the PR states that no admitted component's authority effect, execution effect, or boundary scope changes, and is merged.

Major amendments are adopted only when all of the following occur:

1. Amendment proposal exists.
2. Structural diff exists.
3. Sovereignty compliance verification exists.
4. Boundary impact review exists.
5. Lower-layer impact review exists.
6. Final governance decision exists.
7. New versioned Charter file exists, if the amendment is adopted.
8. Final decision is recorded.
9. PR is merged into main.
10. Supersession statement is added if any prior Charter version is superseded.

Emergency amendments are adopted only when the proposal identifies the underlying class and satisfies that class's adoption requirements, with emergency rationale recorded.

---

## 17. Rejection Procedure

If an amendment is rejected:

- the proposal remains historical record if already committed;
- no authority change occurs;
- prior admitted Charter remains authoritative;
- lower layers must ignore the rejected proposal as authority;
- a new proposal may be drafted only with a new rationale or revised scope.

Rejected proposals must not be silently reintroduced under another name.

---

## 18. Supersession Procedure

A later adopted Charter version may supersede an earlier version.

Supersession must be explicit.

Required statement:

```text
WEAI-Charter-v<new> supersedes WEAI-Charter-v<old> as the active Charter from the merge commit of this adopted amendment.
WEAI-Charter-v<old> remains retained as historical baseline and must not be retroactively mutated.
```

No supersession by implication is allowed.

---

## 19. Versioning Rules

Version increment rules are tied to amendment classes.

| Amendment Class | Version Increment | Example |
|---|---|---|
| Editorial change | patch | v1.0.0 -> v1.0.1 |
| Minor amendment | minor | v1.0 -> v1.1 |
| Major amendment | major | v1.0 -> v2.0 |
| Emergency amendment | follows underlying class as if non-emergency | emergency Major -> next major version; emergency Editorial -> patch |

Emergency amendments do not have their own version increment. The version increment is determined by the underlying class: Editorial, Minor, or Major.

Major versions require the full amendment procedure.

Recommended naming:

```text
WEAI-Charter-v1.0.md
WEAI-Charter-v2.0.md
WEAI-Charter-v3.0.md
```

---

## 20. Commit and PR Hygiene

Charter amendment commits and PRs must follow structural commit hygiene.

They must not include:

- AI tool attribution;
- personal credit attribution;
- Co-authored-by trailers;
- implementation claims outside scope;
- hidden runtime activation;
- unreviewed governance effects;
- mixed source-code changes.

Recommended commit title for this protocol:

```text
docs(governance): add charter amendment protocol
```

Recommended PR title:

```text
docs(governance): add charter amendment protocol
```

---

## 21. Allowed Scope for This Protocol PR

This protocol PR may add:

```text
governance/amendment-protocol.md
```

It must not modify:

```text
README.md
WEAI-Charter-v1.0.md
LICENSE
governance/commit-hygiene-rule.md
```

It must not add:

```text
WEAI-Charter-v2.0.md
CHARTER-V2.0-AMENDMENT-PROPOSAL.md
any file under governance/amendments/
Canon v2.0 documents
Kernel alignment records
Runtime activation records
Registry admission records
Capability admission records
Billing or token records
```

---

## 22. Final Rule

Charter evolution must be explicit, versioned, reviewable, and non-retroactive.

No Charter amendment is valid unless it passes through this protocol.

No lower layer may treat a Charter draft as authority.

No repository may convert ambiguity into permission.

Silence remains non-authorization.  
Ambiguity remains deny.
