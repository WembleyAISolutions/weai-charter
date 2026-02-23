# WEAI Commit Hygiene Rule v1.0

## Structural Commit Integrity Policy

---

## 1️⃣ Structural Commits Are Non-Personal

Structural / Governance layer commits represent:

- System state transition
- Deterministic enforcement change
- Repository boundary evolution
- Architectural stabilization

They do **NOT** represent individual authorship identity.

---

## 2️⃣ Identity & Contact Metadata — Strictly Prohibited

The following are **NOT** allowed in structural commits:

- `Co-authored-by:` footers
- Personal emails
- Company emails
- AI agent attribution
- Tool attribution (Claude, Copilot, etc.)
- Authorization signatures
- Identity metadata of any kind

This applies to:

- Individual contributors
- Company accounts
- Automated agents
- AI-assisted workflows

> Structural commits are system-level state declarations, not personal signatures.

---

## 3️⃣ Allowed Commit Format

Only minimal deterministic commit messages are allowed:

```
type(scope): concise deterministic change description
```

Example:

```
fix(governance): add API response guard and deterministic success log
```

No emoji. No narrative. No promotional language. No identity footer.

---

## 4️⃣ Governance Principle

Governance commits preserve structural sovereignty. They must remain **identity-neutral** and **audit-clean**.
