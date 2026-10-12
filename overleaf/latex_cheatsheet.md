# Workshop LaTeX Cheat Sheet

> **Scope:** A targeted quick-reference guide designed for first- and second-year students customizing the workshop Overleaf resume template. It focuses strictly on the 8 core commands required to edit the template without triggering compilation failures.

---

## 1. Core LaTeX Commands for Resumes

| Purpose | Syntax | Resume Example | Common Mistake |
| :--- | :--- | :--- | :--- |
| **Bold** | `\textbf{text}` | `\textbf{Distributed Systems}` | Forgetting closing brace `}` |
| **Italic** | `\textit{text}` | `\textit{Node.js, Express, MongoDB}` | Using Markdown `*text*` |
| **Emphasis** | `\emph{text}` | `\emph{B.Tech Computer Science}` | Confusing with `\textit` |
| **Line Break** | `\\` | `XYZ University \\ Bangalore, India` | Using `\newline` or multiple enters |
| **Bullet List** | `\begin{itemize}`<br>`  \item Bullet one`<br>`\end{itemize}` | `\begin{itemize}`<br>`  \item Built REST APIs using Express`<br>`\end{itemize}` | Forgetting `\end{itemize}` or missing `\item` |
| **Code Comment** | `% comment text` | `% TODO: Add GitHub link after event` | Missing `%` makes comment visible |
| **Hyperlink** | `\href{URL}{Anchor Text}` | `\href{https://github.com/johndoe}{GitHub}` | Forgetting to escape `%` in URLs |
| **Section Header** | `\section*{Projects}` | `\section*{Technical Skills}` | Modifying preamble styles instead of section argument |

---

## 2. Special Character Escaping (Critical!)

In LaTeX, certain everyday characters are reserved for compiler instructions. You must escape them with a backslash `\` or they will cause a compilation crash:

| Reserved Symbol | Meaning in LaTeX | How to Escape in Your Resume | Example |
| :---: | :--- | :---: | :--- |
| `&` | Alignment tab in tables | `\&` | `C++ \& Python` |
| `%` | Comment indicator | `\%` | `Reduced latency by 15\%` |
| `$` | Math mode toggle | `\$` | `Supported \$500 budget` |
| `#` | Macro parameter | `\#` | `Ranked \#1 in class` |
| `_` | Subscript toggle | `\_` | `user\_controller.js` |

> **Pro Tip:** If your resume suddenly fails to compile after pasting text, search for unescaped `&` or `%` symbols!

---

## 3. Template Customization Quick Guide

When working with the workshop template:
1. **Preamble Protection:** Never edit anything before `\begin{document}` (lines 1–30 containing `\documentclass` and `\usepackage`).
2. **Personal Information:** Locate the header block and replace `John Doe`, phone number, and links.
3. **Updating Projects:**
   * Locate `\resumeProjectHeading` or `\section*{Projects}`.
   * Edit the project title, technology stack argument, and dates.
   * Update bullet items inside the `\resumeItemListStart` ... `\resumeItemListEnd` (or `\begin{itemize}`).
4. **Testing Edits:** Click **Recompile** (or `Ctrl + Enter` / `Cmd + Enter`) after editing each section to catch syntax errors immediately.
