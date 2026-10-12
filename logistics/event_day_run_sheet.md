# Event-Day Master Run Sheet

> **Total Event Window:** 120 Minutes (30m Setup + 75m Core Delivery + 15m Floating Operational Buffer + 15m Teardown)  
> **Target Audience:** 1st- and 2nd-year engineering undergraduates  
> **Master Rule:** Core instructional milestones are locked. The 15-minute operational buffer is held strictly for friction management (account sign-in, Overleaf compile errors, Wi-Fi dropouts).

---

## 1. Timeline Overview

```
T - 30m : AV Setup, Projector Testing, Wi-Fi Verification, Volunteer Briefing
T - 10m : Doors Open, QR Code Displayed, Student Wi-Fi Onboarding
-------------------------------------------------------------------------------
T + 00m : Workshop Kickoff (00–05m Meet John Doe Critique)
T + 05m : Resume Anatomy & Principles (05–12m)
T + 12m : Projects & Skills Selection + Formula (12–25m)
T + 25m : Overleaf Hands-on Demonstration (25–43m)
T + 43m : Independent Student Build Sprint (43–48m)
T + 48m : Google AI Studio Orientation (48–53m)
T + 53m : AI Project Population & Bullet Refinement (53–71m)
T + 71m : Final Checklist & PDF Export (71–75m)
-------------------------------------------------------------------------------
[+15 min Floating Buffer absorbed dynamically across setup / Overleaf / AI segments]
-------------------------------------------------------------------------------
T + 90m : Workshop Adjourned, 1-on-1 Student Assistance
T + 105m: Teardown, Venue Handover, Team Debrief
```

---

## 2. Minute-by-Minute Operational Protocol

### Phase 0: Pre-Event Technical Setup (T - 30m to T - 00m)
* **Lead Facilitator:**
  * Connect laptop to projector (confirm 1080p, text size readable from back row).
  * Open browser tabs: Overleaf project template, Google AI Studio, Slide deck, `John_Doe_Resume.pdf`.
  * Test audio / microphone if lecture hall requires sound amplification.
* **Technical Assistants (TAs):**
  * Check extension cords and power strip distribution across student rows.
  * Test attendee Wi-Fi speed and verify Overleaf and AI Studio are not firewall-blocked.
  * Stand at entrance: ensure attendees open their laptops and display the welcome screen QR code.

---

### Phase 1: Core Instructional Delivery (T + 00m to T + 75m)

#### 00:00 – 05:00 | Meet John Doe (5 mins)
* **Lead:** Project `John_Doe_Resume.pdf`. Give room 20 seconds of silence to critique. Prompt: *“What makes you trust or reject this candidate?”*
* **TAs:** Observe room engagement; guide quiet rows to spot the 15 ungrouped skills.
* **Pacing Check:** Transition sharply at 05:00 to resume principles.

#### 05:00 – 12:00 | Resume Anatomy & Principles (7 mins)
* **Lead:** Walk through standard student section hierarchy. Emphasize: *“A section earns its place by adding evidence of ability.”*
* **Deliverable:** Students complete mental section audit.

#### 12:00 – 25:00 | Projects + Skills Selection (13 mins)
* **Lead:** Introduce the **3-Question Test** (Relevance, Technical Depth, Evidence) and the **Bullet Formula** (`Action + What + How + Result`).
* **Lead:** Contrast weak bullets with factually improved bullets. Reiterate anti-fabrication rule.
* **TAs:** Encourage students to identify their top 2–3 technical projects on paper or text editor.

#### 25:00 – 43:00 | Overleaf Hands-on Demo (18 mins)
* **Lead:** Open template. Demonstrate 3-pane layout, preamble boundary, and 8 basic LaTeX commands.
* **Live Demo:** Modify header live, categorize skills live, demonstrate deliberate compiler error (`}`) and fix.
* **TAs:** **Critical roaming window.** Troubleshoot student Overleaf account login issues or failed initial compiles.

#### 43:00 – 48:00 | Independent Build Sprint (5 mins)
* **Lead:** Start 5-minute countdown timer on screen. Instruct students to populate Name, Education, and rough Project names.
* **TAs:** Actively patrol rows to fix unescaped characters (`&`, `%`) causing compilation errors.

#### 48:00 – 53:00 | Introduce Google AI Studio (5 mins)
* **Lead:** Explain AI as an editorial assistant, not an achievement generator. Walk through the copy-paste Master Prompt.
* **Lead:** Highlight Prompt Rule #7: *“Do NOT invent metrics, users, or technologies.”*

#### 53:00 – 71:00 | AI Project Bullet Refinement (18 mins)
* **Lead:** Demonstrate live conversion of the "College Event Management System" backend notes into 3 bullet variations.
* **Students:** Input their rough project notes into Google AI Studio; select, verify, and copy refined bullets into Overleaf.
* **TAs:** Verify students are not accepting hallucinated metrics from the model. Assist with formatting in LaTeX.

#### 71:00 – 75:00 | Final Checks & Takeaway (4 mins)
* **Lead:** Guide students through the pre-flight checklist. Trigger final Recompile. Walk through PDF download icon.
* **Closing:** *“Your resume is a living document. Keep updating your GitHub links and technical depth.”*

---

### Phase 2: Floating Buffer & Overflow Management (15 mins)
* If the room encounters widespread network lag or login delays during Overleaf (25–43m) or AI Studio (53–71m), the lead absorbs up to 15 minutes of dedicated hands-on troubleshooting without truncating core teaching points.

---

### Phase 3: Post-Session Wrap-Up & Teardown (T + 90m to T + 105m)
* Facilitators stay at the front desk for 15 minutes for 1-on-1 resume critiques.
* Collect feedback forms / anonymous student feedback.
* Pack AV adapters, extension cords; restore room layout; debrief team.
