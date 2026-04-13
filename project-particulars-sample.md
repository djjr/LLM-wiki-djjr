# project-particulars.md — Project Context

_This file holds the project-specific configuration for the LLM wiki engine.
It is read at session startup alongside CLAUDE.md. To adapt the wiki engine
to a new project, copy the skeleton, replace this file, and initialize a new
log entry. CLAUDE.md itself does not need to change._

----
## ★ PROJECT CONTEXT

**Project name:** LLM Role-Playing and Personas

**Substantive focus:**
This wiki covers two interlocking domains that we are thinking about
*analogically* — back and forth — in order to produce original insights in
both:

1. **LLM domain**: role-playing and personas in large language models —
   how they are elicited, what mechanisms underlie them, what they reveal
   about model internals, how they relate to alignment and identity.

2. **Sociology/philosophy domain**: theories of role, role-taking, and
   role structure — Mead, Goffman, Sartre, Natanson, Bourdieu, and others
   who have theorized what it means for a person (or agent) to occupy,
   inhabit, or perform a role.

**The central question this wiki is building toward:**
What can the sociological and philosophical literature on human role-taking
teach us about what happens when an LLM adopts a persona — and vice versa?
What does LLM persona behavior reveal about assumptions buried in the
sociological literature?

**Audience calibration:**
All explanatory writing should be pitched to a post-PhD researcher who is
actively studying this topic with broad expertise in adjacent fields. Do not
over-explain. Assume familiarity with standard ML concepts (attention,
fine-tuning, RLHF, etc.) and with major figures in sociology and philosophy
of mind. Precision and density are virtues. Hedging and hand-holding are not.

**Domain tags to use:**
- `llm` — LLM/ML-side material
- `sociology` — sociological role theory
- `philosophy` — philosophy of mind, action, identity
- `analogy` — pages that explicitly bridge the two domains
- `empirical` — findings from papers or experiments
- `theoretical` — conceptual/theoretical claims