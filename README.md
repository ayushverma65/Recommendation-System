# Task 4 - Movie Recommendation System

A compact content-based recommender. It compares genre tags with Jaccard similarity and returns the most similar titles from the included sample catalog.

## Run

```bash
python3 recommender.py
python3 recommender.py "Arrival"
```

The sample catalog is intentionally small and embedded in the script, so the project works offline. Add movies and genre tags to `MOVIES` to expand it. The demo does not model user ratings or claim production-scale personalization.
