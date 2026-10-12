# Google AI Studio: Master Resume Bullet Prompt Pack

> **Module Time:** Minutes 48–71 (23-Minute Total Allocation)  
> **Tool URL:** [https://aistudio.google.com/](https://aistudio.google.com/)  
> **Guiding Principle:** **AI is an editorial refiner, not an achievement generator.** Never fabricate metrics, users, or technologies.

---

## 1. Copy-Paste Master Prompt (Core Activity: 53–71 min)

Provide this prompt to students to copy and paste directly into Google AI Studio (Gemini 1.5 Flash / Pro model):

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

---

## 2. Optional Secondary Prompt: Bullet Quality & Clarity Audit (Minutes 71–75 or Extra Time)

Use this prompt if students finish early or wish to critique draft bullets:

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

Draft bullets to audit:
[PASTE DRAFT BULLETS HERE]
```

---

## 3. Strict Student Verification Checklist

Before copying any generated bullet into your Overleaf template, verify:
* [ ] Did I personally implement every feature described?
* [ ] Can I explain the technology and architecture on a whiteboard?
* [ ] If a metric is included, did I actually measure it?
* [ ] Does the bullet avoid filler buzzwords (e.g., "synergy", "cutting-edge", "game-changing")?
* [ ] Are special LaTeX characters (`%`, `&`, `_`) properly escaped with backslashes?
