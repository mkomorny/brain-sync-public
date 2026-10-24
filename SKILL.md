---
name: brain-sync
description: >-
  Runs a conversation-opening Second Brain context briefing. Use when the user types 
  /brain-sync or wants to load active tasks, key decisions, and preferences for a 
  topic at the start of a session. Executes immediately with no approval needed.
  Optional: specify a topic name (e.g., "Live Actions", "studio setup").
---

# Brain Sync — Session Context Briefing (`/brain-sync`)

## When invoked

Execute **immediately**. No approval needed.

## Syntax

```
/brain-sync [topic]
```

- `topic`: Project or topic name to focus the briefing (optional; if omitted, use context from the current conversation)

## Execution Steps

1. Identify current project or topic from the argument or active conversation context.
2. Call `recall` with intent: `"User is starting a work session on [topic] — retrieve active tasks, key decisions, preferences, and any outstanding questions or constraints."`
3. Format results into a clean briefing:

```
🧠 Session Context: [topic]

📌 Key Decisions & Rules
  [list decisions]

⚙️ Active Preferences & Setup
  [list preferences/config]

📝 Open Tasks & Follow-ups
  [list tasks]
```

## Examples

```
/brain-sync
/brain-sync Live Actions
/brain-sync studio setup
/brain-sync Ableton OSC bridge
```
