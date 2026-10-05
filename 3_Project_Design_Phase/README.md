# Phase 3 – Project Design

## Architecture Overview
```
User -> Frontend (HTML/CSS/JS + Jinja2)
          -> FastAPI Backend (routes, auth, sessions, CORS)
               -> Gemini Utils (gemini_utils.py: prompts, budget formatting, image analysis)
                    -> Gemini 1.5 Flash Pro
               -> Platform links / mock product data (Amazon, Flipkart, IKEA, Swiggy, Zomato, OYO)
          <- Structured recommendations rendered as cards
```

## Components
| Component | Description |
|-----------|-------------|
| Frontend UI | Forms for budget/preferences/images; card-based result display |
| FastAPI Backend | Routing, JWT auth, sessions, history, communication with Gemini |
| Gemini AI Layer | Understands budget context, analyzes images, generates structured suggestions |
| Platform Integration | Product/service sourcing via links, mock calls or simulated scraping |

## API Endpoints
| Endpoint | Purpose |
|----------|---------|
| `/register`, `/login`, `/logout`, `/token` | Authentication & JWT |
| `/session-info`, `/session-data` | Session metadata and personalization data |
| `/generate-home` | Home interior recommendations |
| `/generate-party` | Party planning recommendations |
| `/generate-jewelry` | Jewelry recommendations (text + image) |
| `/recommendations-details` | Detailed recommendation results |
| `/history` | Past queries and results |

## UI Pages
Home, Testimonials, Register, Login, Dashboard, Home Planner + Recommendations, Party Planner + Recommendations,
Jewelry Planner + Recommendations, History.

UI screenshots are in [`../7_Project_Documentation_Phase/screenshots`](../7_Project_Documentation_Phase/screenshots).
