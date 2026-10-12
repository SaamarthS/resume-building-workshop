# [TASK]: LaTeX Cheat Sheet Finalization & Printable Handout

* **Issue ID:** `TASK-05`
* **Target File(s):** `overleaf/latex_cheatsheet.md`, `overleaf/latex_cheatsheet.pdf`
* **Priority:** `priority: medium`
* **Suggested Labels:** `priority: medium`, `area: overleaf`, `good first issue`, `status: ready`
* **Dependencies:** `facilitator/facilitator_guide.md §9`
* **Suggested Owner:** *Unassigned (Pending organizer assignment)*

---

## Purpose & Context
First- and second-year students easily get stuck on basic LaTeX syntax, such as escaping special characters (`&`, `%`, `_`) and unclosed braces. A standalone, high-contrast cheat sheet (available both on GitHub and as a single-sheet PDF handout/slide) serves as their primary debugging reference during the 43–48m build sprint.

---

## Exact Scope
### In Scope
- Review `overleaf/latex_cheatsheet.md` for clarity and completeness.
- Create a printable 1-page PDF version (`overleaf/latex_cheatsheet.pdf`) suitable for physical printing or mobile viewing.
- Include a high-visibility warning box on character escaping (`\&`, `\%`, `\_`, `\$`, `\#`).
- Provide examples of custom macro editing matching the workshop template.

### Out of Scope
- Documenting advanced LaTeX commands (math matrices, TikZ diagrams, complex tables) not used in the resume template.

---

## Acceptance Criteria
- [ ] Contains all 8 essential commands from the Facilitator Guide.
- [ ] Explicitly highlights the top 5 compilation-breaking characters and their escaped counterparts.
- [ ] Single-page printable PDF generated and stored in `overleaf/latex_cheatsheet.pdf`.
- [ ] Validated by a beginner tester with zero prior LaTeX experience.
