# WEAI Charter

This repository is the constitutional governance repository for the WEAI ecosystem. It defines sovereignty, the constitutional layer hierarchy, amendment procedure, and structural governance hygiene.

It does not implement runtime logic, business logic, or any operational system.

This README is a navigation document. It is not itself a source of authority.

---

## 1. Active Authority

The active admitted Charter is:

```text
WEAI-Charter-v1.0.md
```

This file remains the governing Charter until a later versioned Charter file is adopted through the admitted amendment protocol.

No README wording, draft, branch, or unmerged proposal can amend or supersede the active Charter.

---

## 2. Repository Role

This repository defines:

- sovereignty source;
- admitted governance layer hierarchy;
- amendment procedure;
- structural mutation constraints;
- repository-level governance hygiene.

This repository does not:

- implement any layer below Charter;
- create authority of any kind by README wording, structural placement, directory presence, or documentation implication;
- admit governance components, layers, or boundaries beyond those admitted by the active Charter.

---

## 3. Constitutional Layer Model

The active Charter recognizes five constitutional layers, in strict top-down dependency order:

1. Charter (Sovereignty Layer)
2. Canon (Normative Rules)
3. Kernel (Deterministic Execution Engine)
4. Runtime (Commercial & Policy Enforcement)
5. Registry (Skill & Schema Authority)

Lower layers must not override higher layers.

This list mirrors the active Charter §2. The README does not independently define the layer model.

The terms in this section preserve the active Charter wording. They are not implementation instructions and must not be read as admitting runtime behavior, execution authority, or repository-level operational responsibility.

---

## 4. Historical Boundary Clarification

This repository predates the later separation of `weai-harness` as a downstream validation and enforcement boundary.

Earlier Charter terminology preserves the active constitutional wording and must not be read as implementation placement for later repositories.

Current downstream repository boundaries may clarify how constitutional layer responsibilities are separated in practice, provided they do not amend the active Charter or create authority by implication.

Such clarifications remain non-authorizing unless adopted through the admitted amendment protocol.

---

## 5. Amendment Procedure

The amendment procedure is defined by:

```text
governance/amendment-protocol.md
```

This README does not paraphrase or restate the procedure. For amendment classes, required review artifacts, adoption rules, supersession rules, lifecycle states, and procedural details, refer to the protocol file directly.

---

## 6. Proposal and Review Records

Amendment proposals are recorded under:

```text
governance/amendments/
```

Repository-recorded review artifacts for proposals are stored beside the proposals they review, with explicit naming.

Proposal records and review artifacts are non-authorizing unless adopted under the amendment protocol. Their presence in the repository does not imply adoption, future admission, or pre-acknowledgement of any candidate component.

---

## 7. Commit and PR Hygiene

Commit and PR hygiene is defined by:

```text
governance/commit-hygiene-rule.md
```

All structural commits and PRs in this repository must follow that rule.

---

## 8. Boundary Rules

The following boundary rules apply:

1. Charter authority is explicit, versioned, and admitted.
2. Proposal text is not authority.
3. Review artifacts do not adopt proposals.
4. README text is not an amendment mechanism.
5. Lower layers must not infer authority from ambiguity.
6. Candidate components require explicit admission before they can become governance components.
7. No authority is created by README wording, repository structure, directory presence, planning records, or documentation implication.
8. Authority is created only by the active Charter and by amendments adopted through the admitted amendment protocol.

Ambiguity remains denied.

---

## 9. Stability Policy

This README is a stable repository entrypoint.

It is updated only when:

- a new Charter version is admitted;
- the amendment protocol path or filename changes;
- the repository structure changes in a way that affects the entrypoint;
- the commit hygiene rule changes the repository operating procedure;
- a non-authorizing clarification is required to prevent misreading of repository authority, proposal status, review artifacts, or historical terminology.

Ordinary proposal activity, review activity, planning records, and implementation work do not trigger README updates.

---

## 10. Final Rule

This repository is the entrypoint to WEAI constitutional authority. The active Charter file is the source of authority. This README is a navigation document; it is not authoritative.

This repository is not a product, runtime, business platform, or operational system.

No authority exists here unless admitted by the active Charter or by an amendment adopted through the admitted amendment protocol.
