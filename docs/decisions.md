# Project Decisions Log

This document records architectural, pedagogical, and organizational decisions for the workshop. Each decision outlines the context, rationale, status, and downstream consequences.

---

## Decision Status Legend
* **Confirmed:** Authoritative decision approved and locked into curriculum.
* **Proposed:** Recommended pattern pending final organizer sign-off.
* **Under Discussion:** Open inquiry requiring input.
* **Superseded:** Replaced by a subsequent decision.

---

## Confirmed Decisions

### DEC-01: Master Timing Allocation (75-Minute Core + 15-Minute Floating Buffer)
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Novice engineering students encounter high rates of environment friction (Overleaf compilation bugs, account logins, slow college Wi-Fi, forgotten passwords). Cramming friction resolution into presentation slots derails pedagogical pacing.
* **Decision:** Lock core instructional content to exactly **75 minutes across 8 precise segments**. Allocate a separate, floating **15-minute buffer** dedicated exclusively to onboarding friction, compilation error assistance, and roaming technical support. Total scheduled slot: 90 minutes.
* **Consequences:** Presenters must not add optional content that expands the 75-minute core. Presenters must strictly pace segment transitions.

---

### DEC-02: Substance-First Pedagogy (Content Diagnosis Before LaTeX Syntax)
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Engineering students frequently assume that a LaTeX-formatted resume is automatically high quality, conflating visual typesetting with technical substance.
* **Decision:** Sequence the curriculum so that content critique and bullet drafting precede any LaTeX editing. The workshop begins with an audit of John Doe's resume flaws, project evaluation (3-Question Test), and bullet construction before opening Overleaf.
* **Consequences:** Students understand *what* belongs on a resume before struggling with *how* to typeset it.

---

### DEC-03: Strict Zero-Hallucination AI Studio Policy
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Generative AI tools often fabricate plausible-sounding metrics (e.g., "reduced latency by 45%", "served 10,000 daily active users") or exaggerate junior contributions. Students adding fabricated claims to resumes face severe disqualification risks in technical interviews.
* **Decision:** Frame Google AI Studio strictly as a **stylistic editor and clarity critiquer**, never an achievement generator. The copy-paste master prompt explicitly forbids the model from fabricating metrics, technologies, users, or outcomes. If real metrics do not exist, the student must describe the concrete technical outcome instead.
* **Consequences:** All generated bullet samples must adhere to defensible facts. Reviewers must reject PRs containing fabricated metrics or fake statistics in sample resumes.

---

### DEC-04: Preservation of Weak Sample Resume Content
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** The baseline document `John_Doe_Resume.pdf` is intentionally weak in substance (15 ungrouped skills, 1-line project descriptions, empty claims), but visually clean.
* **Decision:** Maintain the original John Doe content exactly as specified. Do not "fix" or alter `John_Doe_Resume.pdf` or `John_Doe_Resume_Expected_Flaws.txt`. The improved version will live separately in `resumes/improved/`.
* **Consequences:** The opening 0–5 minute critique exercise remains consistent and repeatable.

---

### DEC-05: Minimalist LaTeX Curriculum Scope
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Teaching complete LaTeX in an introductory workshop causes cognitive overload.
* **Decision:** Constrain the LaTeX instruction to the 8 core commands needed to modify the workshop template (`\textbf`, `\textit`, `\emph`, `\\`, `\begin{itemize}/\item`, `%`, special character escaping `\& \% \$ \# \_`, and `\href`). Instruct students not to modify preambles or packages during the session.
* **Consequences:** Reduces compilation error rates; allows first-year students to successfully compile a resume within 18 minutes of hands-on demo time.

---

### DEC-06: Modular Delegation Architecture for Exam Constraints
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Core organizers are taking exams. Team members have limited, fragmented working hours.
* **Decision:** Every deliverable must be represented as a fully specified GitHub Issue with self-contained context, exact scope, acceptance criteria, and zero ambiguity. Work progresses through short-lived branches and pull requests.
* **Consequences:** Volunteers can pick up and complete a task in 30–60 minutes without requiring synchronous meetings.

---

### DEC-07: Strict Separation of Confirmed Facts from Pending Logistics
* **Status:** Confirmed
* **Date:** 2026-10-12
* **Context:** Venue reservations, speaker assignments, and turnout numbers fluctuate before event approval.
* **Decision:** Confirmed pedagogical facts are treated as authoritative. Unknown operational variables are explicitly quarantined as "Unresolved / Pending Decision" rather than fabricated or assumed.
* **Consequences:** Documentation remains honest, accurate, and audit-proof.

---

## Open Decisions Requiring Organizer Input

| ID | Title | Status | Options Under Consideration | Impact |
| :--- | :--- | :--- | :--- | :--- |
| **DEC-OPEN-01** | Presentation Slide Platform | Under Discussion | 1. Google Slides (link in repo)<br>2. Markdown Marp/Slidev (version-controlled)<br>3. LaTeX Beamer | Portability vs. ease of last-minute slide edits by exam-busy team. |
| **DEC-OPEN-02** | Venue & Hardware Infrastructure | Pending | Room selection, projector aspect ratio (16:9 vs 4:3), audio mic type | Determines slide template resolution and live coding visibility. |
| **DEC-OPEN-03** | Workshop Capacity & TA Ratio | Pending | 30 students (1 TA), 60 students (2–3 TAs), 100+ students (4+ TAs) | Affects hands-on support during 43–48m and 53–71m segments. |
| **DEC-OPEN-04** | Attendee Pre-requisite Campaign | Proposed | Send setup checklist 48 hours prior via email/WhatsApp group | Mitigates buffer depletion caused by in-session account signups. |
