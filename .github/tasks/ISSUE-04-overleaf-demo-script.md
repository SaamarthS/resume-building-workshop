# [TASK]: Overleaf Demonstration Script & Template Validation

* **Issue ID:** `TASK-04`
* **Target File(s):** `overleaf/demo_script.md`, `overleaf/starter_template/`
* **Priority:** `priority: high`
* **Suggested Labels:** `priority: high`, `area: overleaf`, `status: ready`
* **Dependencies:** Overleaf project link `https://www.overleaf.com/project/6ac64229826766883d011260`
* **Suggested Owner:** *Unassigned (Pending organizer assignment)*

---

## Purpose & Context
The 18-minute Overleaf demonstration (25–43m) is the highest-friction technical segment for beginners. Facilitators need a rehearsed, step-by-step walkthrough covering the 3-pane interface, the non-negotiable preamble boundary, live edits, and a deliberate syntax error to teach students error recovery.

---

## Exact Scope
### In Scope
- Access the workshop Overleaf template and export its source code into a local backup folder (`overleaf/starter_template/main.tex`).
- Validate that the public share link allows read-only cloning by arbitrary student accounts.
- Rehearse the 18-minute demo script against a timer.
- Document exact line numbers where students must make changes.
- Prepare visual screenshots or backup slides for the deliberate compiler error demo.

### Out of Scope
- Rewriting the template's preamble or installing custom LaTeX packages.

---

## Acceptance Criteria
- [ ] Public Overleaf link verified to open without authentication blocks.
- [ ] Local copy of `.tex` starter template committed to repo as an offline contingency.
- [ ] Script timings verified: 4m UI overview, 4m preamble & header, 5m projects & skills, 3m deliberate compiler error, 2m PDF export.
- [ ] Deliberate error demonstration tested and documented with exact error log output.
