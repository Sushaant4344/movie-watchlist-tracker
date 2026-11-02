# movie-watchlist-tracker

# Movie Watchlist & Review Tracker

A web app for searching films, tracking what to watch, and rating what you've seen.

**Status:** In active development

## Tech Stack
Python, FastAPI, SQL (SQLite), HTML/CSS, Jinja2, TMDB API

## Current Features
- Movie search powered by the TMDB API

## Planned Features
- Watchlist ("Want to Watch" / "Watched")
- Ratings and reviews
- Stats dashboard (average rating by genre, total hours watched)
- User authentication

## Run Locally
1. Clone the repo and create a virtual environment
2. `pip install -r requirements.txt`
3. Add a `.env` file with `TMDB_API_KEY=your_key`
4. `uvicorn app.main:app --reload`

---
*This product uses the TMDB API but is not endorsed or certified by TMDB.*
