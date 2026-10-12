# Project Context: Resume Building × Overleaf × Google AI Studio Workshop

> **Purpose:** This document provides the single, authoritative briefing for all human contributors, workshop facilitators, and AI assistants working on this event.

---

## 1. Project Overview & Mission

* **Event Title:** Resume Building × Overleaf × Google AI Studio Workshop
* **Target Audience:** First- and second-year engineering undergraduate students (principally Computer Science / IT / Circuit branches).
* **Core Value Proposition:** Transitioning students from vague, generic, claim-heavy resumes to high-signal, factual, one-page technical resumes crafted in LaTeX (Overleaf) and refined using Google AI Studio without fabricating claims.
* **Project Nature:** **Event Delivery Project**. This repository does *not* contain an application codebase; it coordinates curriculum development, presenter assets, logistics, quality assurance, and event execution.
* **Operational Constraint:** Key organizers are heavily constrained by ongoing academic examinations. All tasks must be modular, thoroughly scoped, independently executable, and delegated with minimal ambiguity.

---

## 2. Session Architecture & Strict Time Allocation

The workshop follows an exact **75-Minute Core Instructional Schedule** backed by an external **15-Minute Operational Buffer**.

```
[00:00 - 00:75 Core Master Schedule] -------------------------------------------------------------+
| 0-5m  | 5-12m    | 12-25m         | 25-43m          | 43-48m | 48-53m    | 53-71m        | 71-75m |
| John  | Sections | Projects/Skills| Overleaf Syntax | Build  | AI Studio | AI Bullet     | Wrap-up|
| Doe   | & Layout | Selection &    | Hands-On Demo   | Sprint | Intro     | Population    | & PDF  |
| Audit | Strategy | Bullet Formula | & Live Edit     | (Solo) | (Anti-Hal)| (Draft & Edit)| Export |
+-------------------------------------------------------------------------------------------------+
[15-Minute Floating Operational Buffer: Account creation, Overleaf compilation errors, WiFi dropouts]
```

### Detailed Minute-by-Minute Breakdown

| Time Index | Segment Name | Facilitator Objective | Student Deliverable / Activity | Authoritative Reference |
| :--- | :--- | :--- | :--- | :--- |
| **00–05 min** | **Critique John Doe** | Display intentionally weak sample resume; challenge students to spot flaws within 20 seconds. | Students diagnose 15 ungrouped skills, vague bullets, lack of evidence, and empty claims. | `resumes/weak/John_Doe_Resume.pdf` |
| **05–12 min** | **Resume Anatomy & Principles** | Teach the one-page rule, section ordering, relevance criteria, and evidence-first mindset. | Completed section checklist; understanding which sections earn space on a resume. | Facilitator Guide §5 |
| **12–25 min** | **Projects & Skills Selection** | Teach the 3-Question Test (Relevance, Depth, Evidence) and the Bullet Formula (`Action + What + How + Result`). | Students select their best 2–3 projects and categorize technical skills. | Facilitator Guide §6–§7 |
| **25–43 min** | **Overleaf Hands-on Demo** | Guide students through the template, editor UI, compilation cycle, and 8 essential LaTeX syntax patterns. | Students clone/open template, edit personal info, and compile their first live PDF. | Facilitator Guide §8–§10 |
| **43–48 min** | **Independent Build Sprint** | Provide a focused, quiet 5-minute window to populate confirmed education and raw project notes. | Education and raw project drafts inserted into the Overleaf editor. | Facilitator Guide §11 |
| **48–53 min** | **Introduce Google AI Studio** | Frame AI strictly as an **editorial refiner**, *not* an achievement generator. Establish zero-hallucination ground rules. | Students open AI Studio, review the Master Prompt, and prepare factual notes. | Facilitator Guide §12 |
| **53–71 min** | **AI Project Bullet Refinement** | Guide students through iterative prompt execution using raw, factual notes to generate crisp technical bullets. | 2–3 polished, honest, technically descriptive project bullet sets in Overleaf. | Facilitator Guide §12 |
| **71–75 min** | **Final Checks & Takeaways** | Lead final review checklist, compile final PDF, and outline portfolio progression steps. | Compiled, error-free 1-page PDF exported; actionable next steps. | Facilitator Guide §14 |
| **+15 min Buffer** | **Operational Contingency** | **Dedicated troubleshooting window** held outside core timing for login failures, LaTeX debugging, and slow WiFi. | Resolution of compilation blocks and account access issues without stalling the room. | Facilitator Guide §1 |

---

## 3. Core Pedagogical Principles & Non-Negotiables

### A. Substance Over Superficial Design
The weak resume (`John_Doe_Resume.pdf`) is visually tidy and well-aligned. **We do not teach that ugly = weak.** Its weaknesses are purely substantive:
1. 15 mixed, ungrouped skills with zero context.
2. Vague descriptions ("Made a website using React and Node").
3. No evidence of ownership, architectural decisions, or results.
4. Fluff achievements ("Interested in coding", "Good problem solver").

### B. Strict Anti-Hallucination & Anti-Fabrication Rule
When using Google AI Studio:
* **Never invent metrics:** If a student did not measure latency or user adoption, the bullet must *not* claim "improved performance by 35%". Instead, describe the technical outcome (e.g., "implemented REST endpoints to manage user registration").
* **Never invent technologies:** The AI prompt explicitly commands: `Do NOT invent metrics, users, technologies, achievements, results or responsibilities.`
* **Human in the Loop:** Students must verify every word before committing it to their Overleaf source.

### C. The Bullet Writing Formula
Every technical bullet must follow:
$$\text{Action Verb} + \text{What Was Built} + \text{How / Technologies Used} + \text{Result / Technical Outcome}$$

* *Weak:* Developed a website for college events.
* *Better:* Developed a full-stack event management platform using React and Node.js for participant registration and event administration.
* *Best (only when factual):* Developed a full-stack event management platform using React and Node.js, implementing role-based workflows for registration; reduced manual registration overhead.

---

## 4. Source-of-Truth Hierarchy

To prevent conflicting instructions, contributors must respect this order of precedence:

1. **Level 1 (Master Authority):** [Facilitator Guide](file:///d:/Resume%20building%20event/Resume_Building_Overleaf_Google_AI_Studio_Facilitator_Guide.docx) (and transcribed in [`facilitator/facilitator_guide.md`](file:///d:/Resume%20building%20event/facilitator/facilitator_guide.md)). Dictates all timings, scripts, bullet formulas, and prompt wording.
2. **Level 2 (Authoritative Baseline References):**
   * [`John_Doe_Resume.pdf`](file:///d:/Resume%20building%20event/John_Doe_Resume.pdf) — visual baseline.
   * [`John_Doe_Resume_Expected_Flaws.txt`](file:///d:/Resume%20building%20event/John_Doe_Resume_Expected_Flaws.txt) — diagnostic criteria.
   * Overleaf Project Template (`https://www.overleaf.com/project/6ac64229826766883d011260`).
3. **Level 3 (Project Tracking & Decisions):**
   * [`docs/decisions.md`](file:///d:/Resume%20building%20event/docs/decisions.md) — architectural and organizational decisions.
   * [`docs/source_inventory.md`](file:///d:/Resume%20building%20event/docs/source_inventory.md) — asset register.
   * [`ROADMAP.md`](file:///d:/Resume%20building%20event/ROADMAP.md) — deliverables, priorities, and unresolved items.

---

## 5. Team Operating Model

Because core team members are balancing exam commitments:
* **No ad-hoc assignments:** Everything is tracked via GitHub issues in `.github/tasks/`.
* **Zero ambiguity:** Every task issue must contain explicit deliverables, dependencies, and verifiable acceptance criteria.
* **No silent scope creep:** No new tools, extra time blocks, or secondary activities may displace the core 75-minute plan.
