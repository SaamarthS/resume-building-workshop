# [TASK]: Google AI Studio Prompt Pack & Demonstration Assets

* **Issue ID:** `TASK-03`
* **Target File(s):** `ai-studio/master_prompt.md`, `ai-studio/prompt_examples.md`
* **Priority:** `priority: critical`
* **Suggested Labels:** `priority: critical`, `area: ai-studio`, `status: ready`
* **Dependencies:** `facilitator/facilitator_guide.md`
* **Suggested Owner:** *Unassigned (Pending organizer assignment)*

---

## Purpose & Context
During minutes 48–71 of the workshop, students will interact directly with Google AI Studio. Facilitators need verified prompt assets, a clear student verification protocol, and tested live examples to ensure students do not generate hallucinated metrics.

---

## Exact Scope
### In Scope
- Validate the master prompt against Gemini 1.5 Flash in Google AI Studio to ensure consistent adherence to anti-fabrication rules.
- Test edge cases (e.g. what happens when a student inputs notes with zero technical details) and document mitigation prompts.
- Ensure the prompt output strictly produces:
  - Version A: concise
  - Version B: technical
  - Version C: impact/outcome-focused
  - Missing information list
- Prepare copy-pasteable snippets formatted for mobile/laptop screens.

### Out of Scope
- Building custom AI API applications or script integrations (this is an in-browser workshop activity).

---

## Acceptance Criteria
- [ ] Master prompt tested live on [aistudio.google.com](https://aistudio.google.com/) with 3 diverse student inputs.
- [ ] Verbatim prompt matches Facilitator Guide §12.
- [ ] Output includes the required 3 bullet variants + "Missing information" diagnostic.
- [ ] Anti-hallucination constraint strictly tested: model must decline to invent metrics when none are provided in input.
- [ ] Student verification checklist is complete and clear.
