# [TASK]: Improved Model Resume Implementation (LaTeX & PDF)

* **Issue ID:** `TASK-02`
* **Target File(s):** `resumes/improved/improved_resume.tex`, `resumes/improved/improved_resume.pdf`, `resumes/improved/bullet_comparison.md`
* **Priority:** `priority: high`
* **Suggested Labels:** `priority: high`, `area: resume`, `area: overleaf`, `status: ready`
* **Dependencies:** `resumes/weak/expected_flaws.md`, `resumes/improved/README.md`, `overleaf/latex_cheatsheet.md`
* **Suggested Owner:** *Unassigned (Pending organizer assignment)*

---

## Purpose & Context
Students need a tangible, completed demonstration showing how John Doe's flawed profile is transformed into a high-signal, professional technical resume using the exact Overleaf template taught in class.

---

## Exact Scope
### In Scope
- Author `improved_resume.tex` based on the official Overleaf template.
- Compile and verify a crisp 1-page `improved_resume.pdf`.
- Reorganize the 15 ungrouped technologies into Languages, Frameworks, and Tools.
- Upgrade the 3 generic project descriptions into 2–3 technical bullet blocks using `Action + What + How + Result`.
- Author `bullet_comparison.md` providing side-by-side comparisons of weak vs. improved bullets.

### Out of Scope / Strict Constraints
- **Zero Fabrication:** Do NOT invent fake performance metrics (e.g. "boosted conversion by 80%") or fake production scale. If John Doe's projects were student prototypes, describe concrete technical functionality, schemas, and architectures instead.
- Do NOT exceed exactly 1 page.

---

## Acceptance Criteria
- [ ] `improved_resume.tex` compiles cleanly with zero LaTeX warnings/errors.
- [ ] Output PDF is strictly 1 page in length with standard margins.
- [ ] Contains categorized skills (Languages, Frameworks/Libraries, Tools/Platforms).
- [ ] Contains professional contact placeholders (GitHub, LinkedIn, Email).
- [ ] Projects utilize the 4-part bullet formula.
- [ ] Fluff achievements ("interested in coding") are removed and replaced with verifiable technical details or omitted.
- [ ] Side-by-side comparison table committed in `bullet_comparison.md`.
