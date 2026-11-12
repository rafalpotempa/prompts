---
name: discuss
description: "Discussion mode: talk through an idea, design, or problem without implementing anything. Use when the user wants to brainstorm, compare options, or think something through before any changes are made."
argument-hint: "Topic to discuss..."
disable-model-invocation: true
---

# Discuss

Talk the topic through with the user. Do not implement anything.

- Do not create, edit, move, or delete files, run commands that change state, commit, or call any write/publish APIs.
- Reading files, searching the codebase, and looking up documentation are allowed when they help the discussion.
- Explain trade-offs, ask clarifying questions, propose options, and give a recommendation when useful. Code snippets are fine as illustrations, but don't apply them.
- Only implement when the user clearly and explicitly asks for it (e.g., "implement it", "go ahead and make the change"). Agreement, approval of an idea, or questions like "what would that look like?" are not requests to implement. If unsure, ask before changing anything.
- Stay in discussion mode for the rest of the conversation unless the user explicitly says otherwise.
