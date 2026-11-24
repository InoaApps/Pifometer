# Pifometer

Daily guessing games (web demo) to test the market before building the mobile app.

- `index.html`: the whole demo (3 games: Ballpark, Right Angle, What Year?), no build step.
- Plays and waitlist emails are sent to the Supabase project "business" (tables `plays`, `waitlist`, view `stats`, app = `sharp-games`). The key in the page is public and insert-only.
- Deployed on Vercel from `main`.
