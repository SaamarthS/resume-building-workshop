# Overleaf Live Demonstration Facilitator Script

> **Session Segment:** Minutes 25–43 (18-Minute Core Instructional Slot)  
> **Facilitator Target:** Take students from zero LaTeX familiarity to comfortably modifying sections and recompiling without fear of errors.  
> **Official Template Link:** [`https://www.overleaf.com/project/6ac64229826766883d011260`](https://www.overleaf.com/project/6ac64229826766883d011260)

---

## 1. Timeline Breakdown (18 Minutes Total)

```
[00:00 - 04:00] Interface Tour & Mental Model (File tree, editor, PDF viewer, recompile cycle)
[04:00 - 08:00] Preamble vs. Content Boundary & Header Live Edit
[08:00 - 13:00] Editing Projects, Items, and Bullets
[13:00 - 16:00] The "Fearless Debugging" Demo (Deliberate compiler error & log inspection)
[16:00 - 18:00] PDF Export Walkthrough & Handoff to Independent Sprint
```

---

## 2. Step-by-Step Facilitator Protocol

### Step 1: Interface Orientation (4 mins)
* **Action:** Project the Overleaf interface in full-screen mode.
* **Talking Point:** *“LaTeX is not a Word document where formatting is hidden behind menus. It is code that compiles into a publication-grade document. Overleaf gives you three panes: File Tree (left), Source Code (middle), and Compiled PDF (right).”*
* **Key Controls to Point Out:**
  * Recompile button (and green auto-compile toggle).
  * Split-view slider.
  * Download PDF icon.

### Step 2: The Preamble Boundary (4 mins)
* **Action:** Highlight lines 1 through ~30 (above `\begin{document}`).
* **Talking Point:** *“Everything before `\begin{document}` is the engine room—font packages, margins, and custom commands. Rule #1 for today: do not touch the preamble. Your work begins right after `\begin{document}`.”*
* **Live Action:** Locate `\textbf{\Huge John Doe}`. Change it to your own name live. Hit `Ctrl + Enter` (or `Cmd + Enter`). Show the right-hand PDF immediately refreshing.

### Step 3: Editing Projects and Skills (5 mins)
* **Action:** Scroll to the Skills section. Show how 15 comma-separated items can be split into three categorized lines:
  ```latex
  \textbf{Languages}{: Java, Python, C++, JavaScript} \\
  \textbf{Frameworks}{: React, Node.js, Express} \\
  \textbf{Tools}{: Git, Docker, Linux, AWS}
  ```
* **Action:** Scroll to the Projects section. Show how an item is structured:
  ```latex
  \item Built REST endpoints for event registration and integrated MongoDB for persistent storage.
  ```
* Point out that each bullet is simply an `\item` inside a list environment.

### Step 4: The Deliberate Error Demonstration (3 mins)
* **Action:** Intentionally delete a closing brace `}` on a `\textbf{...}` command. Hit **Recompile**.
* **Visual:** A red error badge appears.
* **Talking Point:** *“When LaTeX gives you an error, do not panic. Click on the error message. It will tell you the exact line number. In 90% of cases, you either forgot a closing brace `}` or forgot to escape a special character like `&` or `%`.”*
* **Action:** Add the brace back, recompile, and show the clean PDF.

### Step 5: Exporting the PDF (2 mins)
* **Action:** Click the download icon next to the Recompile button. Show the generated PDF opening in the browser.
* **Transition to Part C (Student Sprint):** *“Now it's your turn. You have 5 minutes to open your copy of the template and fill in your name, education, and raw project names.”*
