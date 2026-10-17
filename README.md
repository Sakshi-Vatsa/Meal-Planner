# Meal Archive — GitHub Pages

A static, privacy-conscious starter website using five historical weekly diet plans (25 May–28 June 2026) provided in Dr. Shikha Singh's emails.

## Deploy
1. Create a **public** GitHub repository, e.g. `meal-archive`.
2. Upload `index.html` to the repository root (or push the contents of this folder).
3. In repository **Settings → Pages**, set **Build and deployment → Deploy from a branch**, branch `main`, folder `/ (root)`; save.
4. Open `https://YOUR_USERNAME.github.io/meal-archive/` once deployment completes.

GitHub Pages is publicly visible. This starter website intentionally excludes identifiable health data. Only publish meal information you are comfortable making public.

## What it includes
- Browse meal options by category and search by dish or ingredient.
- Switch between historical weekly plans and weekdays, with original portions and alternatives.
- Links to original Gmail source emails (which only work for the signed-in account with access).
- Recipe-video index using the links included in source emails.

## Scope and data quality
- Contains **five** example historical plans, **not all 61 emails**.
- The 15–21 June 2026 hummus sandwich quantities look unusual in the original email and are flagged, not silently corrected.
- The weekly plans here repeat the same menu daily as in the messages reviewed. The dated archive is not a recommended current diet.
- This is a static site without login, tracking, or email syncing. Additional plans must be deliberately added to the data array in `index.html`.
