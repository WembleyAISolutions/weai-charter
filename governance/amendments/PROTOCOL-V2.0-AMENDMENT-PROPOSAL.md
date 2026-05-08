# Protocol v2.0 Amendment Proposal

Status: amendment candidate  
Maturity: outline only  
Review state: v0.5 repository-reviewed proposal record; non-adopted and non-authorizing
Target: amendment protocol v2.0  
Repository: weai-charter  
Path: governance/amendments/PROTOCOL-V2.0-AMENDMENT-PROPOSAL.md  
Authority effect: none until adopted through the admitted amendment protocol  
Adoption effect: none by this proposal alone  
Supersedes: none by this proposal alone  

---

## 0. Non-Authorization Statement

This file is an amendment proposal outline only.

It does not:

- amend `governance/amendment-protocol.md`;
- create an amendment protocol v2.0;
- amend `WEAI-Charter-v1.0.md`;
- create any new Charter version;
- admit any new governance component;
- authorize execution;
- activate any lower-layer system;
- issue grants;
- create commercial, operational, or implementation authority.

No local draft, model output, chat message, branch, or unmerged proposal has governance authority.

Protocol v2.0 becomes admitted only if a separate protocol amendment is adopted through the current admitted amendment protocol.

---

## 1. Amendment Title

Protocol v2.0 Amendment Proposal.

Purpose:

```text
Clarify how the amendment protocol may amend itself, classify protocol-target amendment proposals, resolve internal classification ambiguities, and provide a procedurally complete path for future governance proposals without importing substantive ecosystem vision into the protocol layer.
```

---

## 2. Target Protocol Version

Target protocol version:

```text
amendment protocol v2.0
```

Current admitted protocol:

```text
governance/amendment-protocol.md
```

This proposal intentionally records the target as protocol-level rather than Charter-level.

Because the current admitted protocol is primarily written around Charter amendment flow, this proposal preserves the current field vocabulary where useful and marks Charter-specific fields as not applicable when the target is the protocol itself.

---

## 3. Amendment Class

Proposed amendment class:

```text
Major
```

Rationale per current amendment protocol:

- a change to amendment procedure is a major amendment;
- a change to source-of-truth rules is a major amendment;
- a change to what may count as an admitted governance record is a major amendment.

This proposal targets amendment procedure.

Therefore Major class applies, and the full amendment process required for Major amendments must be followed by any future Protocol v2.0 amendment.

This proposal does not itself perform the major amendment.

Reference: see current amendment protocol §4.3 for the canonical Major-class trigger list.

---

## 4. Motivation

This proposal exists because the current protocol is sufficient for Charter amendments, but less explicit for protocol-as-target amendments.

The target improvement is procedural only:

- make protocol self-amendment explicit;
- make proposal lifecycle states more complete;
- clarify editorial, minor, major, and emergency handling;
- resolve internal classification ambiguity in the current protocol;
- clarify required review artifacts by class;
- clarify how impact on other repositories may be reviewed at the procedural level without naming specific repositories or candidate future components.

---

## 5. Problem Statement

The following procedural problems require review:

1. The current proposal template is Charter-centered and does not clearly distinguish Charter-target proposals from protocol-target proposals.

2. The current lifecycle vocabulary does not fully distinguish draft, candidate, in-review, adopted, rejected, withdrawn, deferred, superseded, or stale states.

3. The current protocol can be read as procedurally complete for Charter amendments while still being under-specified for self-amendment, versioning, and abstract downstream impact review.

4. The current protocol treats emergency status as both an amendment class and a versioning modifier. This dual reading creates ambiguity in version increment determination and review artifact requirements. The two readings cannot both govern without a hierarchy rule.

5. The current sovereignty compliance verification wording includes examples of authority effects. Some examples are useful as denials, but Protocol v2.0 should ensure that examples do not become pre-admission of any component, boundary, or authority type. Reference: see current amendment protocol §8 and §15 for the wording in question.

6. The current protocol does not establish a naming convention for proposals whose target is the protocol itself rather than the Charter. The recommended path template uses a Charter-specific prefix and does not generalize to protocol-target proposals.

These problems are procedural. They do not require or authorize any substantive ecosystem positioning.

---

## 6. Affected Protocol Sections

A Protocol v2.0 amendment may need to revise or add sections covering:

- protocol scope, including target type distinction;
- protocol-as-target amendments;
- proposal metadata;
- amendment classes;
- emergency status classification treatment;
- required review artifacts;
- lifecycle states;
- adoption rules;
- rejection rules;
- withdrawal and deferral rules;
- supersession rules;
- versioning rules;
- structural diff requirements;
- sovereignty compliance verification;
- boundary impact review;
- lower-layer impact review;
- cross-repository procedural impact category;
- naming convention for Charter-target versus protocol-target proposals;
- reviewer checklist requirements.

This proposal does not prescribe final text for those sections.

---

## 7. Affected Admitted Governance Components

Affected admitted governance components:

```text
None directly affected by this proposal.
```

Charter v1.0 derivation:

```text
No admitted governance component is changed, renamed, admitted, removed, or repositioned by this proposal.
```

This proposal affects only the proposed procedure for reviewing future protocol amendments.

If a later adopted protocol v2.0 affects admitted components, that effect must be stated explicitly in the final amendment artifact.

---

## 8. Authority Effects

Authority effect before adoption:

```text
None.
```

Authority effect if adopted:

```text
The amendment protocol may gain clearer procedural rules for self-amendment, amendment class handling, lifecycle state handling, review artifacts, and abstract impact review.
```

Not authorized by this proposal:

- no Charter change;
- no new governance component;
- no lower-layer activation;
- no grant issuance;
- no implementation directive;
- no commercial or operational authority.

---

## 9. Non-Effects

This proposal has no effect on:

- active Charter authority;
- admitted component hierarchy;
- lower-layer behavior;
- lower-layer repository implementation;
- registry contents;
- grant issuance;
- execution flow;
- account behavior;
- operational behavior.

This proposal also does not import any vision document, roadmap, product strategy, commercial positioning, or candidate future boundary into the amendment protocol.

---

## 10. Compatibility Statement

This proposal is intended to remain compatible with:

- `WEAI-Charter-v1.0.md`;
- `governance/amendment-protocol.md`;
- `governance/commit-hygiene-rule.md`.

Compatibility requirements:

1. Protocol v2.0 must not reduce the authority of the active Charter.
2. Protocol v2.0 must not create authority by implication.
3. Protocol v2.0 must not admit any new component by procedural wording.
4. Protocol v2.0 must preserve deterministic review and explicit adoption.
5. Protocol v2.0 must preserve structural commit hygiene.

If compatibility cannot be shown, the proposal must be revised or rejected.

---

## 11. Supersession Statement

This proposal does not supersede the current amendment protocol.

A future adopted Protocol v2.0 amendment must include an explicit supersession statement, including:

- prior protocol identifier;
- new protocol identifier;
- adoption date or commit reference;
- scope of supersession;
- preserved obligations;
- changed obligations;
- migration rule for open proposals.

Until that statement exists in an adopted artifact, the current amendment protocol remains authoritative.

Open decision for Protocol v2.0 drafting:

```text
File naming convention for active protocol versus archived prior versions.
```

The current admitted protocol uses path `governance/amendment-protocol.md`, referenced by the repository governance surface. Any naming change must preserve or migrate these references explicitly.

The Protocol v2.0 amendment must record an explicit decision among at least the following candidate approaches, without selecting the choice in this proposal:

- preserve `governance/amendment-protocol.md` as the always-current path and archive prior versions under separate filenames;
- introduce versioned filenames for each version, with the unversioned filename frozen as historical baseline;
- retain a single canonical filename with embedded version metadata only.

This proposal does not select among these candidates. It records the decision as required for any Protocol v2.0 adoption.

---

## 12. Migration Plan

This proposal recommends that any future Protocol v2.0 amendment include a migration rule for existing proposal files.

Migration questions to answer:

1. Do existing open proposals remain valid under their original protocol?
2. Are existing proposals required to add new metadata fields?
3. Are stale or inactive proposals marked withdrawn, deferred, or stale?
4. Are prior rejected proposals protected against silent reintroduction?
5. Are proposal paths preserved or renamed?
6. Are protocol-target proposals distinguished from Charter-target proposals?

This proposal does not perform migration.

---

## 13. Explicit Adoption Rule

A future Protocol v2.0 amendment should state an explicit adoption rule.

Minimum adoption rule:

```text
A protocol amendment is adopted only when the required review artifacts for its amendment class exist, the final governance decision is recorded, and the adopting PR is merged into main.
```

The adoption rule should distinguish:

- editorial amendments;
- minor amendments;
- major amendments;
- emergency amendments;
- protocol-target amendments;
- Charter-target amendments.

Emergency status should reduce delay only where allowed. It must not remove review.

---

## 14. Rollback or Rejection Consequence

If this proposal is rejected:

- no protocol change occurs;
- current amendment protocol remains authoritative;
- future protocol amendment proposals may be submitted separately;
- rejected concepts must not be silently reintroduced under another title.

If this proposal is deferred:

- the proposal remains non-authoritative;
- no implementation or lower-layer work may rely on it;
- future review must state whether it is still current, stale, or superseded.

If this proposal is withdrawn:

- the withdrawn status should be recorded;
- the branch or file may be closed without authority effect;
- any later revival must identify itself as a new proposal or an explicit continuation.

---

## 15. Reviewer Checklist

Reviewers should verify:

1. The proposal is procedural only.
2. The proposal does not amend the active Charter.
3. The proposal does not create protocol v2.0 by itself.
4. The proposal does not admit new governance components.
5. The proposal does not name candidate future components.
6. The proposal does not name external repositories except `weai-charter`.
7. The proposal does not include product, platform, commercial, or roadmap positioning.
8. The proposal does not introduce execution authority.
9. The proposal does not introduce grant authority.
10. The proposal does not introduce account or operational authority.
11. The proposal distinguishes Charter-target and protocol-target amendment questions.
12. The proposal identifies current protocol limitations without rewriting the protocol inline.
13. The proposal preserves current amendment authority until adoption.
14. The proposal includes rejection, deferral, withdrawal, and supersession consequences.
15. The proposal is suitable for short-cycle red-team review before any full Protocol v2.0 drafting.
16. The proposal flags the emergency classification ambiguity for Protocol v2.0 resolution.
17. The proposal flags any current protocol wording that could be misread as pre-admission if examples are treated as admitted boundaries.
18. The proposal flags the absence of a naming convention for protocol-target versus Charter-target proposals.

---

## Section A. Structural Diff Summary

Required table form for a later full amendment:

| Area | Prior Protocol | Proposed Protocol | Effect |
|---|---|---|---|
| Protocol scope target distinction | Charter-centered scope wording | Explicit scope coverage of protocol-as-target amendments | Procedural clarification |
| Protocol target handling | Charter-centered proposal vocabulary | Explicit protocol-target handling | Procedural clarification |
| Lifecycle states | Limited status vocabulary | Expanded lifecycle states | Procedural clarification |
| Amendment classes | Existing class structure | Clearer class boundaries and adoption mapping | Procedural clarification |
| Emergency classification | Ambiguous class/modifier treatment | Single canonical treatment | Procedural clarification |
| Self-amendment | Implicit or under-specified | Explicit protocol self-amendment rule | Procedural clarification |
| Review artifacts | Existing review artifact list | Artifact requirements by class and target | Procedural clarification |
| Sovereignty compliance wording | Example-driven question wording | Generic wording consistent with non-pre-admission principle | Procedural clarification |
| Cross-repository impact category | Lower-layer review only | Procedural cross-repository impact category | Procedural clarification |
| Versioning | Existing version rules | Explicit mapping between amendment class and version increment, including emergency disposition | Procedural clarification |
| Supersession | Existing supersession handling | Explicit protocol supersession and migration rule | Procedural clarification |
| Proposal naming convention | Charter-prefixed template only | Naming convention covering Charter-target and protocol-target proposals | Procedural clarification |

This table is an outline only. It does not amend the protocol.

---

## Section B. Sovereignty Compliance Verification

A later full Protocol v2.0 amendment must answer these questions:

1. Does the amendment preserve active Charter authority?
2. Does the amendment avoid creating authority by implication?
3. Does the amendment avoid admitting new components?
4. Does the amendment avoid lower-layer activation?
5. Does the amendment preserve explicit adoption and rejection?
6. Does the amendment preserve deterministic review artifacts?
7. Does the amendment preserve structural commit hygiene?
8. Does the amendment define its own migration and supersession effect?
9. Does the amendment apply the non-pre-admission principle to its own text, including review-question wording?

If any answer is unclear, the amendment should be treated as not ready for adoption.

---

## Section C. Boundary Impact Review

Boundary impact classification:

```text
No new admitted boundary is created by this proposal.
```

A later full Protocol v2.0 amendment should classify only abstract procedural effects, such as:

- no change;
- clarification only;
- procedural requirement added;
- procedural requirement removed;
- review artifact changed;
- lifecycle state changed;
- adoption rule changed;
- supersession rule changed;
- migration rule changed.

It must not use the protocol to pre-admit substantive governance components or candidate future boundaries.

---

## Section D. Lower-Layer Impact Review

Lower-layer impact classification:

```text
None affected by this proposal.
```

A later full Protocol v2.0 amendment must include lower-layer impact review before adoption.

This outline does not perform that review.

---

## 16. Final Proposal Statement

This proposal requests review of a future amendment protocol v2.0 path.

It is intentionally procedural, vision-agnostic, repository-agnostic beyond `weai-charter`, and non-authorizing.

It exists to improve amendment safety, self-amendment clarity, lifecycle discipline, review completeness, internal classification consistency, naming-convention clarity, and migration handling.

Until adopted through the current admitted amendment protocol, it has no governance authority beyond proposal status.
