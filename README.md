# Brain Sync

> **Tri-Platform Agent Skill** for Claude Desktop / Code, Grok CLI, and Google Antigravity / Gemini.  
> Session-Opening Task, Decision, and Constraint Briefing — Runs a session-opening Second Brain context briefing, loading active tasks, key decisions, rules, and preferences for a topic at conversation start.

---

## Overview

`brain-sync` provides standardized capabilities across conversational AI platforms:
- Topic-scoped briefing compiler (/brain-sync [topic]).
- Retrieval of active tasks, constraints, and settled architectural decisions.
- Grounding conversational context to prevent repeating settled debates.
- Tri-platform NTFS junctions connecting Claude, Grok, and Antigravity.
- Standard documentation suite: SKILL.md, HOW_TO_USE.txt, IMPLEMENTATION_PLAN.md, and README.md.

---

## Tri-Platform Architecture

Zero duplicate code across platforms. Canonical source resides in `.agents`:
- **Canonical Source**: `C:\Users\<you>\.agents\skills\brain-sync`
- **Claude**: `C:\Users\<you>\.claude\skills\brain-sync` (NTFS Junction)
- **Grok**: `C:\Users\<you>\.grok\skills\brain-sync` (NTFS Junction)
- **Antigravity**: `C:\Users\<you>\.gemini\config\skills\brain-sync` (NTFS Junction)

---

## Documentation Suite

- [`HOW_TO_USE.txt`](HOW_TO_USE.txt): Standardized user guide and prompt templates.
- [`IMPLEMENTATION_PLAN.md`](IMPLEMENTATION_PLAN.md): Feature checklist and roadmap.
- [`App Changes Tracker.html`](App%20Changes%20Tracker.html): Interactive visual version log.
- [`SKILL.md`](SKILL.md): Agent system instructions and triggers.
