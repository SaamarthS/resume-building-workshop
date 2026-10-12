# Resume Building × Overleaf × Google AI Studio Workshop

[![Session Duration](https://img.shields.io/badge/Duration-75m%20Core%20%2B%2015m%20Buffer-blue)](PROJECT_CONTEXT.md)
[![Target Audience](https://img.shields.io/badge/Audience-1st%20%26%202nd%20Year%20Engineers-green)](PROJECT_CONTEXT.md)
[![Philosophy](https://img.shields.io/badge/AI%20Policy-Zero%20Fabrication-orange)](ai-studio/master_prompt.md)
[![Status](https://img.shields.io/badge/Project%20Status-Milestone%202%20Active-purple)](ROADMAP.md)

Welcome to the collaborative planning repository for the **Resume Building × Overleaf × Google AI Studio Workshop**.

This project prepares, coordinates, and delivers an intensive, hands-on workshop tailored for first- and second-year undergraduate engineering students. The session guides attendees through critiquing weak resumes, structuring high-signal technical projects, typesetting a one-page resume in LaTeX via Overleaf, and using Google AI Studio as an editorial assistant without fabricating claims.

> **Project Notice:** This is an event-delivery and curriculum coordination repository, not a software application codebase.

---

## Workshop Objectives

1. **Substance Over Layout:** Dispel the myth that neat formatting rescues generic content. Teach students to evaluate resume substance using honest evidence.
2. **LaTeX Demystification:** Teach students how to navigate Overleaf and master the 8 core LaTeX commands needed to maintain a publication-grade technical resume.
3. **High-Signal Project Formulation:** Train students to filter projects using the **3-Question Test** (Relevance, Technical Depth, Evidence) and write bullets using `Action + What + How + Result`.
4. **Zero-Hallucination AI Editing:** Introduce Google AI Studio strictly as an editorial refiner. Enforce the non-negotiable rule: **Never invent metrics, users, or technologies**.

---

## 75-Minute Session Architecture (+15-Minute Buffer)

```
[00:00 - 00:75 Core Master Schedule] -------------------------------------------------------------+
| 0-5m  | 5-12m    | 12-25m         | 25-43m          | 43-48m | 48-53m    | 53-71m        | 71-75m |
| John  | Sections | Projects/Skills| Overleaf Syntax | Build  | AI Studio | AI Bullet     | Wrap-up|
| Doe   | & Layout | Selection &    | Hands-On Demo   | Sprint | Intro     | Population    | & PDF  |
| Audit | Strategy | Bullet Formula | & Live Edit     | (Solo) | (Anti-Hal)| (Draft & Edit)| Export |
+-------------------------------------------------------------------------------------------------+
[15-Minute Floating Operational Buffer: Account creation, Overleaf compilation errors, WiFi dropouts]
```

| Time Slot | Segment Name | Student Milestone / Outcome |
| :---: | :--- | :--- |
| **00–05 min** | **Meet John Doe** | Diagnose substantive flaws in an intentionally weak sample resume within 20 seconds. |
| **05–12 min** | **Resume Anatomy & Principles** | Understand the 1-page standard, section hierarchy, and evidence-first mindset. |
| **12–25 min** | **Projects & Skills Selection** | Select top 2–3 defensible projects; categorize technical skills into scan-friendly groups. |
| **25–43 min** | **Overleaf Hands-On Demo** | Master 8 core LaTeX commands; learn error debugging without touching preambles. |
| **43–48 min** | **Independent Build Sprint** | 5-minute focused sprint populating contact info, education, and raw project titles. |
| **48–53 min** | **Introduce Google AI Studio** | Master the prompt framework; establish zero-hallucination ground rules. |
| **53–71 min** | **AI Bullet Refinement** | Transform rough project notes into 2–3 polished, technical, honest resume bullets. |
| **71–75 min** | **Final Checks & Takeaways** | Run pre-flight checklist, recompile, download final PDF, and capture next steps. |
| **+15 min** | **Floating Buffer** | Troubleshoot account sign-ins, Wi-Fi drops, and LaTeX syntax errors without stalling the room. |

---

## Repository Navigation

```
├── .github/                   # GitHub templates, project automation, and task issues
│   ├── ISSUE_TEMPLATE/        # Standardized issue templates
│   ├── tasks/                 # Self-contained, actionable deliverable issues ready to claim
│   └── pull_request_template.md # PR checklist enforcing zero fabrication
├── docs/                      # Architectural decisions, asset inventory, and project records
│   ├── decisions.md           # Confirmed ADRs and open decisions log
│   └── source_inventory.md    # Master inventory of all project source materials
├── facilitator/               # Instructor guides, scripts, and pedagogical resources
│   ├── facilitator_guide.md   # Authoritative workshop curriculum and facilitator transitions
│   └── README.md
├── slides/                    # Presentation deck architecture and slide-by-slide outline
│   └── README.md
├── resumes/                   # Sample resumes used for training and comparison
│   ├── weak/                  # John Doe baseline PDF and expected flaws answer key
│   └── improved/              # Model improved resume specifications (TeX + PDF)
├── overleaf/                  # LaTeX cheat sheets, demo scripts, and starter template links
│   ├── latex_cheatsheet.md    # 8 core commands + special character escaping rules
│   ├── demo_script.md         # Minute-by-minute facilitator demo protocol
│   └── README.md
├── ai-studio/                 # Google AI Studio prompts, constraints, and live examples
│   ├── master_prompt.md       # Master copy-paste prompt and verification checklist
│   ├── prompt_examples.md     # Worked backend & ML bullet transformation examples
│   └── README.md
├── logistics/                 # Run sheets, technical checklists, and student prep guides
│   ├── event_day_run_sheet.md # Minute-by-minute coordinator protocol (120m total)
│   ├── technical_checklist.md # AV, projector, Wi-Fi, and emergency offline pack
│   ├── student_preparation_guide.md # 48-hour pre-workshop student onboarding copy
│   └── README.md
├── PROJECT_CONTEXT.md         # Master briefing document for contributors and AI agents
├── ROADMAP.md                 # Deliverables matrix, priorities, dependencies, and questions
├── CONTRIBUTING.md            # Lightweight 7-step contribution workflow
└── README.md                  # This file
```

---

## How to Contribute

We welcome contributions from workshop organizers, speakers, and student developers! Because our core team is balancing university exams, we operate through a lightweight, modular issue workflow:

1. Check our active [Roadmap](ROADMAP.md) and browse ready tasks in [`.github/tasks/`](.github/tasks/).
2. Review our [Contribution Guide](CONTRIBUTING.md) for branch naming, PR conventions, and quality gates.
3. Claim an issue, implement the deliverable, and submit a pull request!
