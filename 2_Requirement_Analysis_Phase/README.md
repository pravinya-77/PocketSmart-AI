# Phase 2 – Requirement Analysis

## Functional Requirements
- FR1: User registration, login, logout (JWT token based, session info).
- FR2: Home Interior Planner – budget, room types, item quantities -> recommendations.
- FR3: Party Planner – budget, guests, event type, venue -> catering/decor/entertainment plan.
- FR4: Jewelry Planner – budget, occasion, style, optional outfit image -> recommendations.
- FR5: Recommendation details page and per-user history.
- FR6: Fallback/default recommendations if the AI returns insufficient results.
- FR7: Product links to platforms (Amazon, Flipkart, IKEA, Swiggy, Zomato, OYO, ...).

## Non-Functional Requirements
- Responsive, easy-to-use UI; fast responses; secure credential storage; modular, maintainable code; CORS enabled.

## Software Requirements
| Item | Detail |
|------|--------|
| Language | Python 3.x |
| Backend | FastAPI, Uvicorn |
| AI | Google Gemini 1.5 Flash Pro (text + image) |
| Frontend | HTML, CSS, JavaScript, Jinja2 templates |
| Config | python-dotenv (`.env`) |

## Prerequisites
Google Cloud / Google AI Studio account with Gemini API key; Python basics; FastAPI knowledge.
