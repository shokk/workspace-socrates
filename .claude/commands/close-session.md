---
name: close-session
description: "Close the current Council session: record the dialogue, capture insights, note open threads, and update memory."
user_invocable: true
---

# /close-session — Close the Dialogue

Run these steps in order before ending the session.

## 1. Sweep open threads

Review the session for anything unresolved:

- Questions posed but not fully examined
- Contradictions surfaced but not resolved
- Topics the user deferred ("let's come back to this")
- Disagreements within the Council left open

## 2. Write the session log

Create the entry at:

```
memory/YYYY-MM-DD-<slug>.md
```

- `YYYY-MM-DD` — today's date
- `<slug>` — short kebab-case description of the session's main theme

Required sections:

- **Interlocutor:** Who was Ernie today — what was he wrestling with?
- **Questions examined:** List the main questions explored
- **Insights surfaced:** What emerged that was genuinely new or clarifying?
- **Council positions:** Where did Socrates, Plato, and Aristotle agree or disagree?
- **Aporia reached:** Any productive dead-ends worth noting?
- **Open threads:** Checkboxes for anything unresolved
- **Next session seeds:** Questions worth returning to

## 3. Update MEMORY.md

If the session surfaced something durable — a recurring theme, a significant insight, a pattern in Ernie's thinking — distill it into `MEMORY.md`.

Do not copy raw notes. Distill. What is worth carrying forward?

## 4. Update USER.md

If the session revealed something new about Ernie — his philosophical background, what he actually cares about, how he reasons, what he resists — note it under the appropriate philosopher's observations in `USER.md`.

## 5. Sign off

Tell Ernie the session is closed and summarize:

- Session log written: `<path>`
- Open threads count and quick titles
- Anything added to MEMORY.md
- A parting thought from one of the three philosophers, fitting the session's theme
