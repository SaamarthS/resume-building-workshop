# Contributing to the Workshop Project

Thank you for helping prepare and deliver the **Resume Building × Overleaf × Google AI Studio Workshop**!

Because our core organizing team is balancing academic examinations, we use an asynchronous, self-contained contribution workflow designed to minimize blockers and keep tasks modular.

---

## The 7-Step Contribution Process

Follow these steps to contribute a deliverable or fix:

```
1. Claim Issue  ──> 2. Read Scope ──> 3. Branch ──> 4. Focused Change ──> 5. Open PR ──> 6. Review ──> 7. Merge
```

### 1. Find or Claim an Available Issue
* Browse the issues list in the GitHub repository or review pre-prepared tasks in [`.github/tasks/`](.github/tasks/).
* Find an unassigned issue marked `status: ready` or `good first issue`.
* Comment on the issue to request assignment before starting work to avoid duplicate effort.

### 2. Read Scope and Acceptance Criteria
* Review the issue description carefully.
* Pay strict attention to the **Deliverables**, **Dependencies**, and **Acceptance Criteria**.
* If anything is ambiguous, comment on the issue or ask a project lead before writing code or materials.

### 3. Create a Branch for the Task
* Create a clean branch from `main`:
  ```bash
  git checkout main
  git pull origin main
  git checkout -b task/<issue-number>-<short-description>
  ```
* Examples:
  * `task/01-slide-deck`
  * `task/04-improved-resume-tex`
  * `fix/latex-cheatsheet-escaping`

### 4. Make a Focused Change
* Work only on the files within the issue's defined scope.
* Avoid unrelated refactoring or changing unaffected directories.
* Ensure all files follow repository Markdown and LaTeX formatting standards.

### 5. Open a Pull Request Linking the Issue
* Push your branch to GitHub:
  ```bash
  git push -u origin task/<issue-number>-<short-description>
  ```
* Open a Pull Request targeting `main`.
* Use the provided PR template and link your issue in the description (e.g., `Closes #1` or `Resolves .github/tasks/ISSUE-01-slide-deck.md`).

### 6. Request Review
* Request a review from an organizer or designated peer reviewer.
* Address any feedback or requested changes promptly.

### 7. Merge Only After Review and Validation
* A pull request may only be merged when:
  * All acceptance criteria are verified.
  * The PR has at least one approving review.
  * No non-negotiable project rules are violated (see Quality Gates below).

---

## Non-Negotiable Quality Gates

Every pull request is audited against these four project rules:

1. **Zero Fabrication:** Never introduce fake metrics, fictitious users, or exaggerated achievements into sample resumes, prompts, or presentation materials. If a project was not deployed to production, describe the concrete technical outcome instead.
2. **Timing Integrity:** Do not alter the 75-minute core instructional schedule (+15-minute buffer) or insert optional activities that displace core curriculum modules.
3. **Preserve Original Sources:** Never overwrite or modify the master source files (`Resume_Building_Overleaf_Google_AI_Studio_Facilitator_Guide.docx`, `John_Doe_Resume.pdf`, `John_Doe_Resume_Expected_Flaws.txt`).
4. **Distinguish Facts from Proposals:** Clearly label unconfirmed event logistics (venue, date, speaker names) as *Pending* or *Unresolved*. Never invent event logistics.
