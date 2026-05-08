# WEAI Charter Repository Map

## 1. Purpose

This document maps the repository entrypoints and governance record locations for the WEAI Charter repository.

It exists to reduce ambiguity about repository structure, document location, and interpretation boundaries.

This document is a navigation record only.

It is not a source of authority.

---

## 2. Authority Status

The active admitted Charter remains:

```text
WEAI-Charter-v1.0.md
```

No repository map, README wording, directory structure, filename, proposal record, review artifact, draft, branch, or unmerged pull request can amend or supersede the active Charter.

Authority exists only where admitted by the active Charter or by an amendment adopted through the admitted amendment protocol.

---

## 3. Repository Scope

This repository is the constitutional governance repository for the WEAI ecosystem.

It may contain:

- the active Charter;
- amendment procedure records;
- amendment proposal records;
- review artifacts;
- repository hygiene rules;
- navigation and repository-structure records.

This repository does not implement:

- runtime logic;
- business logic;
- operational behavior;
- any implementation system below the Charter layer.

---

## 4. Top-Level Repository Map

| Path | Role |
|---|---|
| `WEAI-Charter-v1.0.md` | Active admitted Charter |
| `README.md` | Repository navigation entrypoint |
| `governance/amendment-protocol.md` | Amendment procedure record (admitted) |
| `governance/amendments/` | Amendment proposal and review record location |
| `governance/commit-hygiene-rule.md` | Commit and PR hygiene rule (admitted) |
| `governance/REPOSITORY-MAP.md` | Repository structure navigation map |

The status of each file or directory is derived from the active Charter and the admitted governance records, not from this map. This map does not create or assign status.

---

## 5. Governance Directory Map

```text
governance/
├── amendment-protocol.md
├── amendments/
├── commit-hygiene-rule.md
└── REPOSITORY-MAP.md
```

This map is descriptive only.

It does not create authority by directory presence.

It does not admit future files by implication.

It does not reserve authority for absent files.

---

## 6. Amendment Records

Amendment proposals and review artifacts are recorded under:

```text
governance/amendments/
```

Records in this directory are non-authorizing unless adopted through the admitted amendment protocol.

A proposal file does not imply:

- admission;
- future admission;
- partial adoption;
- pre-acknowledgement;
- implementation readiness;
- repository boundary admission.

A review artifact does not adopt a proposal.

---

## 7. Repository Interpretation Rules

The following interpretation rules apply to this repository map:

1. The active Charter remains the source of constitutional authority.
2. The README remains a navigation document.
3. This repository map remains a navigation document.
4. Directory presence does not create authority.
5. File presence does not create authority.
6. Proposal presence does not imply adoption.
7. Review presence does not imply adoption.
8. Historical references do not admit new constitutional components.
9. Ambiguity remains denied.

---

## 8. Boundary Against Misreading

This repository map must not be read as defining, authorizing, or activating any operational behavior, implementation behavior, or authority not explicitly admitted by the active Charter.

Any such interpretation is denied unless explicitly admitted by the active Charter or by an amendment adopted through the admitted amendment protocol.

---

## 9. Stability Policy

This repository map should be updated only when:

- a mapped repository path changes;
- a new admitted governance record location is created;
- an existing mapped path is renamed or removed;
- a clarification is required to prevent structural or authority misreading.

Ordinary proposal activity, review activity, planning records, or implementation work do not require updates to this map.

---

## 10. Final Rule

This document maps repository structure for navigation.

It does not create, modify, expand, or transfer authority.

No authority exists by repository map wording, repository structure, directory presence, filename, planning record, or documentation implication.
