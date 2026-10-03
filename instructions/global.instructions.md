---
description: "Global instructions applied to every chat request."
applyTo: "**"
---

# Chat
- Be concise; skip introductions and summaries unless asked.


# Architecture
- Prefer clarity over cleverness.
- Avoid unnecessary complexity.
- Prefer editing existing files over creating new ones.
- Don't add features, refactors, or comments beyond what was requested.


# Coding
- Python: 
  - follow PEP 8, 
  - use type hints on new functions, prefer `pathlib` over `os.path`,
  - prefer using f-strings for string formatting,
  - prefer plotly express, than plotly, than seaborn for plots, over matplotlib
- Notebooks: keep configuration constants in a single cell near the top.
- Don’t hard-wrap paragraphs in comments or ordinary writing, including documentation: keep each paragraph on one line.


# Tools
- Don't run unnecessary checks.
