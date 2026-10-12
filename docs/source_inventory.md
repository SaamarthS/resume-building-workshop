# Source Inventory

This document records all source materials present in the workshop repository, establishing their authoritative status, purpose, content integrity, and any unresolved dependencies.

---

## Inventory Summary

| File Path | Purpose | Current Status | Classification | Missing Information / Dependencies |
| :--- | :--- | :--- | :--- | :--- |
| `Resume_Building_Overleaf_Google_AI_Studio_Facilitator_Guide.docx` | Core curriculum, pedagogical goals, timing, script, prompt, and learning outcomes | Complete | **Authoritative Source** | Venue, final speaker names, date/time confirmation |
| `John_Doe_Resume.pdf` | Weak sample resume used in the opening 0–5 minute critique exercise | Complete | **Authoritative Reference (Pedagogical Baseline)** | Needs LaTeX source version documented for Overleaf comparison |
| `John_Doe_Resume_Expected_Flaws.txt` | Facilitator answer key and flaw breakdown for John Doe resume | Complete | **Authoritative Reference** | None |
| Overleaf Template (`https://www.overleaf.com/project/6ac64229826766883d011260`) | LaTeX resume starter template shared with students | External Link (Verified in Guide) | **Authoritative Resource** | Needs local backup/export `.tex` file in repository to prevent link rot |
| Google AI Studio (`https://aistudio.google.com/`) | Platform used for AI-assisted bullet point refinement | External Web App | **External Dependency** | Internet connectivity verification, student Google account access |

---

## Detailed File Analysis

### 1. Facilitator Guide
* **Path:** `Resume_Building_Overleaf_Google_AI_Studio_Facilitator_Guide.docx`
* **Size:** ~34 KB (237 lines extracted text)
* **Status:** Authoritative master document.
* **Key Contents:**
  * Strict session structure: **75-minute core session + 15-minute external buffer**.
  * Complete 8-part session breakdown (0–5m critique, 5–12m resume anatomy, 12–25m projects/skills, 25–43m Overleaf hands-on, 43–48m student build sprint, 48–53m Google AI Studio intro, 53–71m AI project population, 71–75m closing & final checks).
  * 3-Question Test for project selection (Relevance, Technical Depth, Evidence).
  * Bullet formula: `Action + What + How/Technology + Result/Impact`.
  * Official Google AI Studio Master Prompt with strict anti-hallucination rules.
  * Overleaf command cheat sheet (8 key syntax patterns).
  * Facilitator script snippets and transitions.
  * Resource pack with documentation links.
* **Dependencies & Gaps:**
  * Specific event logistics (room, projector requirements, date, volunteer names) are pending.

---

### 2. Weak Sample Resume
* **Path:** `John_Doe_Resume.pdf`
* **Size:** ~32 KB (1-page PDF)
* **Status:** Complete, frozen pedagogical baseline.
* **Integrity Rule:** **DO NOT MODIFY OR VISUALLY DEGRADE.** The layout is intentionally clean; its pedagogical weakness lies entirely in substantive content flaws (generic bullets, no metrics, unsupported claims, 15 ungrouped skills).
* **Profile Summary:**
  * Candidate: John Doe, Computer Science Student, Bangalore, India.
  * Education: B.Tech CSE, XYZ University, 2025–2029, CGPA: 8.6.
  * Skills: 15 mixed technologies in a single comma-separated line (Python, Java, C++, HTML, CSS, JavaScript, React, Node, SQL, MongoDB, AWS, Docker, Git, TensorFlow, Linux).
  * Projects: E-Commerce Website ("Made a website using React and Node."), ML Disease Prediction ("Created a machine learning model using Python."), To-Do App ("Built a to-do list using HTML, CSS and JavaScript.").
  * Achievements: "Participated in hackathons.", "Interested in coding.", "Good problem solver."
* **Missing Information / Dependencies:**
  * Corresponding `.tex` source file should be committed under `resumes/weak/` so facilitators can open it in Overleaf during live demos.

---

### 3. Expected Flaws Answer Key
* **Path:** `John_Doe_Resume_Expected_Flaws.txt`
* **Size:** ~5.7 KB (79 lines)
* **Status:** Complete answer key for facilitators.
* **Core Teaching Points:**
  1. Too many skills, with no categories (15 ungrouped technologies; listing != competence).
  2. Generic project descriptions (no technical depth, no personal contribution).
  3. No evidence of results or impact (no outcomes, metrics, or repository links).
  4. Project selection is not justified (no clear hierarchy or target alignment).
  5. Achievements section contains filler (vague interest claims instead of verifiable facts).
  6. No targeting or clear direction.
  7. Limited evidence of ownership (individual vs. team contribution unknown).
  8. Content precision issues ("Node" vs "Node.js", vague "ML Disease Prediction").
  9. Resume sections and missing evidence (CGPA stated, but no links or GitHub provided).
  10. 7 recruiter diagnostic questions to prompt students.
* **Dependencies & Gaps:**
  * Formatted markdown reference needed in `facilitator/` and `resumes/weak/` for easier readability across devices.

---

## Verification & Preservation Policy

1. **Original Source Preservation:** The root files (`.docx`, `.pdf`, `.txt`) are strictly preserved in their original state.
2. **Derivative Works:** All Markdown versions in `docs/`, `facilitator/`, `resumes/`, `overleaf/`, and `ai-studio/` are derived directly from these sources and cross-referenced.
3. **Fact Verification:** Any proposed addition not found in these three sources is explicitly classified as an *Assumption* or *Proposal* in `ROADMAP.md` and `PROJECT_CONTEXT.md`.
