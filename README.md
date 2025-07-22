# ✅ Pull Request Review Checklist

> _Use this checklist to ensure the PR is complete and meets quality standards. Reviewers can check items during review._

---

## 📌 PR Information
- [ ] PR title is clear and descriptive.
- [ ] PR description includes:
  - [ ] Problem statement.
  - [ ] Summary of the solution.
  - [ ] Related issue/ticket (if applicable).
- [ ] PR is scoped to a single concern (not too large).

---

## 🧩 Code Quality
- [ ] Code is easy to understand and self-explanatory.
- [ ] Function and variable names are meaningful.
- [ ] No redundant, commented, or dead code.
- [ ] Code is modular and follows separation of concerns.

---

## 🎨 Code Style & Consistency
- [ ] Follows project linting and formatting rules.
- [ ] Consistent naming, spacing, and structure.
- [ ] Code style matches existing codebase.

---

## 🔒 Security
- [ ] Inputs are validated and sanitized.
- [ ] No sensitive data (tokens, credentials) committed.
- [ ] No information leaks in logs or error messages.

---

## 🚀 Functionality
- [ ] Code works as intended and solves the issue.
- [ ] Handles edge cases and failures gracefully.
- [ ] Tested manually or in staging (if applicable).

---

## 🧪 Testing
- [ ] New features or fixes include relevant tests.
- [ ] Existing tests pass (CI green).
- [ ] Tests cover both success and failure cases.

---

## 📖 Documentation
- [ ] Comments explain non-obvious logic.
- [ ] Public methods/components are documented.
- [ ] README/docs updated if necessary.

---

## 📂 Architecture & Dependencies
- [ ] Follows folder/module conventions.
- [ ] No unused or unnecessary dependencies added.
- [ ] Design decisions are explained if not obvious.

---

## 🔁 Merge Readiness
- [ ] All conflicts resolved.
- [ ] Clean Git history (rebased/squashed if needed).
- [ ] Ready to merge into base branch.

---

## 📝 Optional Review Tags

| Tag             | Description                                    |
|------------------|------------------------------------------------|
| 🔧 Needs changes | Critical issues found                          |
| 🆗 Looks good     | Meets expectations                             |
| ❓ Needs context | Needs clarification or more information       |
| 🚫 Block merge   | Code introduces bugs or risks, do not merge    |

---

_Thanks for contributing!_
