# Meal Planner — complete historical meal catalogue

A static GitHub Pages website containing every distinct meal-and-portion entry extracted from the 49 matched diet-plan emails (2024–2026).

## Deploy

1. Replace the root `index.html` file in `Sakshi-Vatsa/Meal-Planner` with the one in this package.
2. Commit changes to `main`.
3. GitHub Pages → Deploy from branch `main`, folder `/ (root)`.

The website runs entirely in the browser with no API keys, tracking, or build dependencies.

## Included

- `index.html`: fully browsable searchable meal library with recipe links
- `data/all-meals.json`: structured database, including original email IDs
- `data/all-meals.csv`: import-friendly meal table
- `coverage-report.json`: coverage validation across every source email

Each original source's daily cells are deduplicated by exact category and normalized full meal instructions. Different portion sizes are **not** merged. The original source email IDs are preserved.

## Important

This is a historical meal catalogue, not current dietary guidance. Some emailed video links may be outdated, and video matching is best-effort; the full original recipe references remain in `data/all-meals.json`.
