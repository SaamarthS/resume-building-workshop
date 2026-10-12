# Facilitator Guide: Resume Building × Overleaf × Google AI Studio

> **Format:** 75-Minute Instructional Session + 15-Minute Operational Buffer  
> **Target Audience:** 1st- and 2nd-year engineering undergraduate students  
> **Authoritative Source:** Transcribed from `Resume_Building_Overleaf_Google_AI_Studio_Facilitator_Guide.docx`  
> **Core Purpose:** Give first- and second-year students a practical introduction to building a one-page technical resume in Overleaf, understanding which projects and skills belong on it, and using Google AI Studio to turn rough project information into strong, factual resume bullets.

---

## 1. Session at a Glance

| Time | Segment | Facilitator Goal | Student Output |
| :--- | :--- | :--- | :--- |
| **0–5 min** | **Meet John Doe** | Show a deliberately weak sample resume and get students spotting problems. | Students identify substantive issues. |
| **5–12 min** | **What belongs on a student resume?** | Explain sections, one-page principle, relevance, and evidence. | Section checklist understood. |
| **12–25 min** | **Projects + Skills** | Teach project selection, bullet writing, skill grouping, and credibility. | Students choose 2–3 projects. |
| **25–43 min** | **Overleaf hands-on** | Open the template and teach only the LaTeX commands needed to edit it. | Students edit template. |
| **43–48 min** | **Build your first draft** | Give students a short independent editing sprint. | Basic resume populated. |
| **48–53 min** | **Introduce Google AI Studio** | Explain AI as an editor, not an achievement generator. | Prompt + project notes ready. |
| **53–71 min** | **AI Project Population** | Students feed project notes into AI Studio and improve bullets. | 2–3 polished project entries. |
| **71–75 min** | **Final check + takeaway** | Run a final checklist and explain next steps. | Exported PDF / action list. |
| **+15 min Buffer** | **Operational Support** | Held outside core schedule for account creation, login issues, compilation errors, slow internet, or assistance. | Unblocked attendees. |

---

## 2. Learning Outcomes

1. **Overleaf Workflow:** Navigate an Overleaf project and understand the editor, PDF preview, recompile, file tree, and download/share workflow.
2. **LaTeX Syntax:** Recognize the basic LaTeX syntax used in a resume: commands, braces, environments, comments, line breaks, bold/italics, and lists.
3. **Project & Skill Selection:** Choose projects and skills based on relevance, technical depth, and evidence rather than simply listing everything they have tried.
4. **Bullet Formulation:** Write project bullets using `Action + What + How/Technology + Result/Impact`, without fabricating metrics.
5. **AI Editorial Mastery:** Use Google AI Studio to turn rough, factual project notes into concise resume-ready bullets and critique clarity.

---

## 3. Facilitator Preparation Checklist

- [ ] Prepare one completed John Doe resume PDF and one intentionally weak version.
- [ ] Prepare the Google AI Studio prompt in a copy-paste document or slide.
- [ ] Ask students to bring a laptop, have an Overleaf account, and have 3–4 projects in mind. (They do *not* need polished descriptions in advance).
- [ ] Have a sample job description ready for an optional final comparison if time permits.

---

## 4. Part A — Meet John Doe: What's Wrong With This Resume?

Show the following fictional resume before explaining any rules. Ask students to diagnose it first within 20 seconds.

### John Doe Resume Content
```text
JOHN DOE
Computer Science Student | Bangalore, India

EDUCATION
B.Tech CSE, XYZ University, 2025–2029, CGPA 8.6

SKILLS
Python, Java, C++, HTML, CSS, JavaScript, React, Node, SQL, MongoDB, AWS, Docker, Git, TensorFlow, Linux

PROJECTS
E-Commerce Website
- Made a website using React and Node.

ML Disease Prediction
- Created a machine learning model using Python.

To-Do App
- Built a to-do list using HTML, CSS and JavaScript.

ACHIEVEMENTS
- Participated in hackathons.
- Interested in coding.
- Good problem solver.
```

### Facilitator Diagnostic Questions
* What makes you trust this resume?
* Which project would you remove first, and why?
* What is missing from the project bullets?
* Is listing 15 technologies automatically impressive?
* Which statements are claims rather than evidence?
* If you were a recruiter with 20 seconds, what would you notice?

### Expected Issues to Draw Out
| Problem | Teaching Point |
| :--- | :--- |
| **Too many skills** | A long list does not prove competence. Keep technologies that are relevant and defensible. |
| **Generic project bullets** | “Made a website” says little about the person's contribution or technical depth. |
| **No evidence** | Strong bullets explain what was built, how it was built, and what happened as a result. |
| **Weak project selection** | A project should demonstrate useful skills and preferably show complexity, ownership, or relevance. |
| **No targeting** | The strongest projects/skills depend partly on the internship or role being targeted. |
| **Unnecessary filler** | Statements such as “good problem solver” are weaker than evidence from projects, competitions, or achievements. |

---

## 5. What Should a Student Resume Contain?

Recommended order for most first- and second-year technical students:
1. **Name + professional contact links** (Email, GitHub, LinkedIn, Portfolio)
2. **Education** (Degree, University, Dates, CGPA)
3. **Technical Skills** (Categorized by Languages, Frameworks, Tools)
4. **Projects** (2–3 strongest, technical, defensible projects)
5. **Experience / Positions of Responsibility** (if applicable)
6. **Achievements / Certifications / Relevant Activities** (only if verifiable and evidence-backed)

> **Rule:** Do not force every section onto every resume. A section earns its place by adding evidence of ability or relevance.

---

## 6. Choosing Projects: The 3-Question Test

Teach students to score each project from 1–5:

| Criterion | Question | Strong Signal |
| :--- | :--- | :--- |
| **Relevance** | Does this project support the kind of role I want? | Uses skills requested by target role. |
| **Technical Depth** | Does it demonstrate meaningful engineering / problem solving? | Architecture, algorithms, APIs, ML, databases, systems, deployment. |
| **Evidence** | Can I explain exactly what I did and defend the technologies? | Clear personal contribution, GitHub/demo, metrics if real. |

*Rule of thumb:* **2–3 strong projects are usually more useful than 6 shallow projects.**

### Project Bullet Formula
$$\textbf{ACTION} + \textbf{WHAT YOU BUILT} + \textbf{HOW / TECHNOLOGY} + \textbf{RESULT / IMPACT}$$

* **Weak:** Developed a website for college events.
* **Better:** Developed a full-stack event management platform using React and Node.js for participant registration and event administration.
* **Best (only when factual):** Developed a full-stack event management platform using React and Node.js, implementing role-based workflows for registration and event administration; reduced manual registration work by 40%.

> **Critical Instruction:** Never invent metrics, users, performance gains, technologies, or outcomes. If there is no real metric, describe the concrete technical result instead.

---

## 7. Skills: What to Include

Use categories so the reader can scan quickly:
* **Languages:** Java, Python, C++, JavaScript
* **Frameworks/Libraries:** React, Node.js, TensorFlow
* **Tools/Platforms:** Git, Docker, Linux, AWS

> **Facilitator Rule:** If a student cannot answer basic interview questions about a technology they list, it should not be prominent on their resume.

---

## 8. Part B — Overleaf Hands-On

* Template: `https://www.overleaf.com/project/6ac64229826766883d011260`
* Objective: Teach enough syntax to confidently customize this template, not all of LaTeX.

### Facilitator Sequence:
1. Open the project and identify the file tree, main `.tex` file, source editor, PDF preview, and Recompile button.
2. Point out the preamble (document class and packages). Explain that students should **not** change these during the workshop.
3. Show where actual resume content begins.
4. Change John Doe's name and one project live; recompile and show the PDF updating.
5. Edit one bullet and demonstrate that LaTeX uses commands rather than Word-style formatting.
6. Show one intentional mistake (e.g. unclosed brace `{`) and how the error/log helps locate it.

---

## 9. Basic LaTeX Cheat Sheet for the Workshop

| Purpose | Syntax | Resume Example |
| :--- | :--- | :--- |
| **Bold** | `\textbf{...}` | `\textbf{SmartPace}` |
| **Italic** | `\textit{...}` | `\textit{TensorFlow}` |
| **Emphasis** | `\emph{...}` | `\emph{Research Intern}` |
| **Line break** | `\\` | `Name \\ CSE Student` |
| **Bullet list** | `\begin{itemize} ... \item ... \end{itemize}` | Project bullet list |
| **Comment** | `% comment` | `% temporary note` |
| **Special characters** | `\&  \%  \$  \#  \_` | `C++ \& Python` |
| **Hyperlink** | `\href{URL}{text}` | `\href{https://github.com/...}{GitHub}` |
| **Sectioning** | `\section*{...}` | Used if template relies on standard sections |

*Facilitator Note:* If the template wraps these inside custom macros (e.g. `\resumeProjectHeading`), show students how to edit the macro arguments.

---

## 10. What Students Must Learn About the Template
- Where to replace personal information.
- Where to add/remove a project.
- Which part controls project title, tech stack, dates, and bullets.
- How to add another `\item`.
- How to bold or italicize a word without breaking the template.
- How to add a hyperlink if the template supports it.
- How to recompile and inspect the PDF.
- How to download the finished PDF.

---

## 11. Part C — Student Build Sprint (5 minutes)

Ask students to populate only the content they already know:
* Name + contact links
* Education
* Categorized skills
* 2–3 selected project names
* 1–2 achievements/positions if relevant

> Facilitator circulates and helps with Overleaf syntax, not with ghostwriting.

---

## 12. Part D — Google AI Studio: 15–20 Minute Project Population

**Transition line:** *“We now have the structure and the facts. AI will help us express those facts clearly; it will not invent the facts.”*

### Copy-Paste Master Prompt
```text
You are helping me write resume bullets for a Computer Science student.
I will give you factual notes about a project.

Your job:
1. Identify the strongest technical aspects.
2. Write 2–3 concise resume bullet alternatives.
3. Use Action + What + How/Technology + Result/Impact.
4. Prioritize the student's own contribution.
5. Keep bullets concise and technical.
6. Use strong action verbs.
7. Do NOT invent metrics, users, technologies, achievements, results or responsibilities.
8. If a useful result is missing, do not fabricate one; describe the technical outcome instead.

Project notes:
[PASTE YOUR NOTES HERE]

Target role:
[SOFTWARE / ML / WEB / DATA / OTHER]

Output:
- Version A: concise
- Version B: technical
- Version C: impact-focused
- Missing information that would strengthen the bullet
```

### Live Demonstration Example
**Raw Input:**
```text
Project: College Event Management System
I worked on the backend.
Used Node.js, Express and MongoDB.
Built registration APIs.
Added an admin dashboard.
Worked with two teammates.
No real performance metric.
```

**Expected Bullet Style:**
* Developed backend APIs for a college event management system using Node.js, Express, and MongoDB, supporting participant registration and administrative workflows.
* Implemented REST endpoints for event registration and integrated MongoDB for persistent participant and event data.
* Collaborated with a 3-member team to design and integrate backend functionality with the application frontend.

---

## 13. Optional AI Resume Check (if ahead of schedule)

```text
Review these project bullets for a software engineering internship.
Check:
- technical specificity
- clarity
- unnecessary words
- evidence of ownership
- measurable impact
- relevance
Do not invent missing information.
Return the top 3 improvements and a revised version.
```
*(If time is tight, skip this. The core AI activity is project bullet population).*

---

## 14. Facilitator Script Snippets & Transitions

* **Opening:** *“Today we are not starting with LaTeX. We are starting with the question: what is actually worth putting on a resume?”*
* **John Doe:** *“Before I tell you what's wrong, I want you to reject John Doe yourselves. You have 20 seconds.”*
* **Projects:** *“A project is not impressive because the title sounds impressive. It is impressive when you can explain the problem, your contribution, the technology and the result.”*
* **Overleaf:** *“Now that we know what we want to say, let's learn how to control how it appears.”*
* **AI Studio:** *“AI is not going to create achievements for you. It is going to help you communicate the achievements you already have.”*
* **Closing:** *“Your resume is a living document. Keep the Overleaf source, keep improving your projects, and tailor the content to the roles you apply for.”*

---

## 15. Resource Pack & Links

* **Overleaf — Learn LaTeX:** [https://www.overleaf.com/learn](https://www.overleaf.com/learn)
* **Overleaf — Learn LaTeX in 30 Minutes:** [https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes](https://www.overleaf.com/learn/latex/Learn_LaTeX_in_30_minutes)
* **Overleaf — Commands:** [https://www.overleaf.com/learn/latex/Commands](https://www.overleaf.com/learn/latex/Commands)
* **Overleaf — Commands and Environments:** [https://www.overleaf.com/learn/latex/Commands_and_environments](https://www.overleaf.com/learn/latex/Commands_and_environments)
* **Overleaf — Bold, Italics and Underlining:** [https://www.overleaf.com/learn/latex/Bold%2C_italics_and_underlining](https://www.overleaf.com/learn/latex/Bold%2C_italics_and_underlining)
* **Google AI Studio:** [https://aistudio.google.com/](https://aistudio.google.com/)
* **Google AI for Developers — Files API:** [https://ai.google.dev/gemini-api/docs/files](https://ai.google.dev/gemini-api/docs/files)
* **Workshop Overleaf Starter Template:** [https://www.overleaf.com/project/6ac64229826766883d011260](https://www.overleaf.com/project/6ac64229826766883d011260)
