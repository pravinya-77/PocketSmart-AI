# Phase 4 – Project Planning

| Milestone | Activities | Deliverable |
|-----------|-----------|-------------|
| 1. Gemini AI Initialization | Create Google Cloud/AI Studio account, generate API key, validate text + image prompt calls | Working Gemini connection |
| 2. Core Functionalities | Planner logic in `gemini_utils.py`, home/party/jewelry functions, auth routes, modular structure | Backend core |
| 3. FastAPI Backend Integration | Routes, models, CORS, static files, session handling, startup/main | `main.py` |
| 4. UI Development | HTML/Jinja2 templates, forms, card-style results | `templates/`, `static/` |
| 5. Testing & Optimization | Real-world budgets, prompt tuning, validations, fallbacks | Test report |
| 6. Documentation & Demo | Project report, screenshots, demo video | Docs + demo |

## Risks & Mitigation
| Risk | Mitigation |
|------|------------|
| AI returns irrelevant / over-budget items | Prompt tuning, budget validation |
| API quota/limit errors | Retry and fallback recommendations |
| Invalid user input | Form + server-side validation |
