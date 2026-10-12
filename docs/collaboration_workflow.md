# GitHub Collaboration Workflow & Board Setup

> **Target:** A lightweight, frictionless collaboration framework enabling busy student organizers to asynchronously coordinate workshop deliverables during exam periods.

---

## 1. GitHub Project Board Architecture

Configure a GitHub Projects (v2) Kanban board named **`Workshop Delivery Board`** with the following 5 columns:

```
+---------------+---------------+---------------+---------------+---------------+
|    Backlog    |     Ready     |  In Progress  |   In Review   |     Done      |
+---------------+---------------+---------------+---------------+---------------+
| Ideas, future | Fully-scoped  | Active branch | PR open, peer | Merged to     |
| iterations,   | tasks ready   | in development| review in     | main, quality |
| post-event    | to be claimed | by an assignee| progress      | verified      |
| concepts      |               |               |               |               |
+---------------+---------------+---------------+---------------+---------------+
```

### Column Definitions & Transitions
1. **Backlog:** Tasks or improvements that are not yet refined, post-event ideas, or secondary optional enhancements.
2. **Ready:** Issues that have explicit deliverables, dependencies satisfied, and clear acceptance criteria. Any volunteer with free time can claim these without waiting for a synchronous meeting.
3. **In Progress:** Issues currently being worked on. Rule: Assign yourself to the issue before moving it here, and link your working branch `task/<id>-<slug>`.
4. **In Review:** Pull request opened and linked to the issue. Requires at least one peer review verifying the Quality Gates.
5. **Done:** Pull request merged into `main`. Acceptance criteria verified.

---

## 2. Standard Label Taxonomy

> **Important Rule:** Labels categorize work by priority and domain; they are **never** substitutes for clear acceptance criteria inside the issue description.

### Priority Labels
| Label | Color | Description |
| :--- | :--- | :--- |
| `priority: critical` | `#B60205` (Dark Red) | Blocks the event delivery or core curriculum (e.g. Slides, Run sheet, Venue). |
| `priority: high` | `#D93F0B` (Orange) | Essential educational artifact (e.g. Improved resume, AI prompt pack). |
| `priority: medium` | `#FBCA04` (Yellow) | Important supporting material (e.g. Handout cheat sheet, student prep guide). |
| `priority: low` | `#0E8A16` (Green) | Nice-to-have visual polish or post-event enhancement. |

### Domain / Area Labels
| Label | Color | Description |
| :--- | :--- | :--- |
| `area: slides` | `#1D76DB` (Blue) | Presentation deck visuals, speaker notes, and timing cues. |
| `area: resume` | `#5319E7` (Purple) | Resume content, flaw analysis, and improved LaTeX examples. |
| `area: overleaf` | `#006B75` (Teal) | LaTeX syntax, Overleaf starter template, and live coding demos. |
| `area: ai-studio` | `#D4C5F9` (Light Purple) | Google AI Studio prompts, constraints, and live bullet transformations. |
| `area: logistics` | `#C5DEF5` (Soft Blue) | Venue AV, Wi-Fi verification, run sheet, and student onboarding communications. |
| `area: docs` | `#0052CC` (Deep Blue) | Architecture records, source inventory, and contribution guidelines. |

### Contributor Accessibility Labels
| Label | Color | Description |
| :--- | :--- | :--- |
| `good first issue` | `#7057FF` (Indigo) | Bite-sized tasks suitable for first-time student contributors (e.g., proofreading cheat sheet). |
| `help wanted` | `#008672` (Sea Green) | Tasks requiring specialized skills (e.g. LaTeX typesetting or graphic design). |

---

## 3. GitHub Setup Instructions (Step-by-Step)

Because this repository was prepared in a local workspace, complete the following steps once the repository is pushed to GitHub:

### Step A: Initialize Git & Push to Remote
```bash
# 1. Initialize local git repository
git init
git branch -M main

# 2. Add files and make initial commit
git add .
git commit -m "feat: complete workshop architecture, curriculum docs, and task issues"

# 3. Link to your GitHub remote repository (replace with your repo URL)
git remote add origin https://github.com/<your-org-or-username>/resume-building-workshop.git

# 4. Push to main
git push -u origin main
```

### Step B: Create Standard Labels via GitHub CLI (`gh`)
Run this in PowerShell or terminal with `gh` installed:
```bash
gh label create "priority: critical" --color "B60205" --description "Blocks event delivery or core curriculum" --force
gh label create "priority: high" --color "D93F0B" --description "Essential educational deliverable" --force
gh label create "priority: medium" --color "FBCA04" --description "Important supporting material" --force
gh label create "priority: low" --color "0E8A16" --description "Nice-to-have or post-event polish" --force

gh label create "area: slides" --color "1D76DB" --description "Presentation deck and speaker notes" --force
gh label create "area: resume" --color "5319E7" --description "Resume samples and flaw analysis" --force
gh label create "area: overleaf" --color "006B75" --description "LaTeX syntax and Overleaf template" --force
gh label create "area: ai-studio" --color "D4C5F9" --description "Google AI Studio prompts and examples" --force
gh label create "area: logistics" --color "C5DEF5" --description "Venue, AV, Wi-Fi, and run sheets" --force
gh label create "area: docs" --color "0052CC" --description "Documentation and architecture records" --force
gh label create "status: ready" --color "0E8A16" --description "Fully scoped and ready to be claimed" --force
```

### Step C: Batch-Create the 8 Prepared Issues via `gh` CLI
```bash
gh issue create --title "[TASK]: Workshop Presentation Slide Deck Implementation" --body-file ".github/tasks/ISSUE-01-slide-deck.md" --label "priority: critical,area: slides,status: ready"
gh issue create --title "[TASK]: Improved Model Resume Implementation (LaTeX & PDF)" --body-file ".github/tasks/ISSUE-02-improved-sample-resume.md" --label "priority: high,area: resume,area: overleaf,status: ready"
gh issue create --title "[TASK]: Google AI Studio Prompt Pack & Demonstration Assets" --body-file ".github/tasks/ISSUE-03-ai-studio-prompt-pack.md" --label "priority: critical,area: ai-studio,status: ready"
gh issue create --title "[TASK]: Overleaf Demonstration Script & Template Validation" --body-file ".github/tasks/ISSUE-04-overleaf-demo-script.md" --label "priority: high,area: overleaf,status: ready"
gh issue create --title "[TASK]: LaTeX Cheat Sheet Finalization & Printable Handout" --body-file ".github/tasks/ISSUE-05-latex-cheat-sheet.md" --label "priority: medium,area: overleaf,good first issue,status: ready"
gh issue create --title "[TASK]: Event-Day Run Sheet Protocol & Speaker Coordination" --body-file ".github/tasks/ISSUE-06-event-day-run-sheet.md" --label "priority: high,area: logistics,status: ready"
gh issue create --title "[TASK]: Workshop Curriculum & Materials Peer Review" --body-file ".github/tasks/ISSUE-07-materials-peer-review.md" --label "priority: high,area: resume,area: ai-studio,area: overleaf,status: ready"
gh issue create --title "[TASK]: Logistics, Venue, and Network Verification Sign-Off" --body-file ".github/tasks/ISSUE-08-logistics-venue-verification.md" --label "priority: critical,area: logistics,status: ready"
```

### Step D: Set Up GitHub Projects Board
1. In your GitHub repository, navigate to the **Projects** tab.
2. Click **New project** -> select the **Board** layout.
3. Name it `Workshop Delivery Board`.
4. Ensure the columns are: `Backlog`, `Ready`, `In progress`, `In review`, `Done`.
5. Add the newly created issues to the board into the **Ready** column.
