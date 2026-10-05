# PocketSmart AI – Your Smart Budget & Recommendation Assistant

A GenAI-powered, cross-platform recommendation system that gives personalized, **budget-based** suggestions for
**Home Interiors**, **Party Planning** and **Jewelry**, using **Google Gemini 1.5 Flash Pro**, a **FastAPI** backend
and a **Jinja2 (HTML/CSS/JS)** frontend.

## Project Phases (submission structure)

| # | Phase | Folder |
|---|-------|--------|
| 1 | Brainstorming & Ideation | [1_Brainstorming_Ideation_Phase](1_Brainstorming_Ideation_Phase) |
| 2 | Requirement Analysis | [2_Requirement_Analysis_Phase](2_Requirement_Analysis_Phase) |
| 3 | Project Design | [3_Project_Design_Phase](3_Project_Design_Phase) |
| 4 | Project Planning | [4_Project_Planning_Phase](4_Project_Planning_Phase) |
| 5 | Project Development | [5_Project_Development_Phase](5_Project_Development_Phase) |
| 6 | Project Testing | [6_Project_Testing_Phase](6_Project_Testing_Phase) |
| 7 | Project Documentation | [7_Project_Documentation_Phase](7_Project_Documentation_Phase) |
| 8 | Project Demonstration | [8_Project_Demonstration_Phase](8_Project_Demonstration_Phase) |

## Tech Stack
FastAPI · Uvicorn · Jinja2 · Google Gemini 1.5 Flash Pro · JWT authentication · HTML/CSS/JavaScript

## Quick Start
```bash
cd 5_Project_Development_Phase/src
python -m venv venv
venv\Scripts\activate        # Windows  (Linux/Mac: source venv/bin/activate)
pip install -r requirements.txt
cp .env.example .env          # add your GEMINI_API_KEY
uvicorn main:app --reload
```
Open http://127.0.0.1:8000

> Never commit your real `.env` / API key. Use `.env.example` only.
