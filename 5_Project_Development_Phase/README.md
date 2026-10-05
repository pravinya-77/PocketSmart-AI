# Phase 5 – Project Development

All source code of PocketSmart AI goes in [`src/`](src).

Expected layout (as described in the project document):
```
src/
  main.py              # FastAPI app, routes, auth, sessions, startup
  gemini_utils.py      # Gemini prompts, home/party/jewelry recommendation logic
  requirements.txt
  .env.example         # GEMINI_API_KEY=your_key_here  (do NOT commit real .env)
  templates/           # Jinja2 HTML pages
  static/              # CSS, JS, images
```

## Milestones implemented
1. Gemini AI setup & connectivity
2. Core planner functionality (Home, Party, Jewelry)
3. FastAPI backend (auth, JWT, sessions, history)
4. HTML/Jinja2 UI

## Run
See the root [README](../README.md#quick-start).
