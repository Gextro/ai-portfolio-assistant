# 💬 Aria — AI Portfolio Assistant

An interactive, anime-styled AI assistant that answers questions about **Gourav Goyal** —
his skills, projects, and experience. Built as a single, dependency-free page and hosted on
GitHub Pages.

**🔗 Live:** https://gextro.github.io/ai-portfolio-assistant/

## Features
- 🌸 Animated anime-style avatar (DiceBear, CC BY 4.0)
- 💬 Chat UI with typing indicator and quick-reply chips
- 🧠 Built-in intent-matching engine (keyword scoring over a curated knowledge base) —
  works instantly with **no API key and no server**
- 🔗 Deep-links to all four of Gourav's live projects

## How it works
User text is normalized and scored against a set of intents (skills, projects, experience,
each project, contact, "why hire", …). The best-matching intent returns a grounded answer
from the knowledge base, with a graceful fallback that guides the user.

## Upgrade path
Swap the local matcher for a real LLM by adding a small backend that proxies an
OpenAI-compatible API (e.g. Groq) — the UI stays the same.

## Run locally
Just open `index.html` in a browser. No build step.
