# JV Submissions — Creative Owners Club

Static site (no build step) for JV lead submissions, backed by Supabase and hosted on Render.

- `index.html` — public JV lead form. Submits via the `submit_jv` RPC; underwriting (MAO) is calculated server-side.
- `admin.html` — admin login (Supabase email/password) and submissions table. Access is enforced by RLS.
- `config.js` — Supabase URL and publishable key.
- `render.yaml` — Render blueprint (free static site, publishes repo root).

Run locally by serving the folder, e.g. `npx serve .`
