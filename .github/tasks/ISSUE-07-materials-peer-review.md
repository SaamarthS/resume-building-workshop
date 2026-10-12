# [TASK]: Workshop Curriculum & Materials Peer Review

* **Issue ID:** `TASK-07`
* **Target File(s):** All files in `slides/`, `resumes/`, `overleaf/`, `ai-studio/`, `logistics/`
* **Priority:** `priority: high`
* **Suggested Labels:** `priority: high`, `area: resume`, `area: ai-studio`, `area: overleaf`, `status: ready`
* **Dependencies:** `TASK-01`, `TASK-02`, `TASK-03`, `TASK-04`, `TASK-05`
* **Suggested Owner:** *Unassigned (Pending peer reviewer assignment)*

---

## Purpose & Context
Before publishing or conducting a live rehearsal, all educational materials must pass a formal peer review to guarantee alignment with the Facilitator Guide, ensure zero fabricated claims, and verify that all links and code compile cleanly.

---

## Exact Scope
### In Scope
- Conduct a cross-material consistency audit:
  1. Does the slide deck match the Facilitator Guide minute-by-minute?
  2. Does the AI Studio prompt in `ai-studio/master_prompt.md` match the slide deck text verbatim?
  3. Are all 8 LaTeX cheat sheet commands demonstrated correctly?
  4. Is the weak resume (`John_Doe_Resume.pdf`) strictly distinguished from the improved resume?
  5. Are all internal and external markdown links functioning?
  6. Are any credentials, private email addresses, or secrets committed?

---

## Acceptance Criteria
- [ ] Peer review sign-off checklist completed and documented in a PR review.
- [ ] Zero instances of fabricated metrics found in sample resumes or slide examples.
- [ ] Verified that Overleaf template URL and Google AI Studio URLs resolve cleanly.
- [ ] Confirmed that all repository cross-references use correct relative paths.
