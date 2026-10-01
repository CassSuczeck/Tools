# Safe Travels tools

Public home of Safe Travels Mobile Repair's customer tools, served by GitHub Pages at **tools.besafetravels.com**.

- `/` — placeholder (not indexed) until the tools launch.
- `/calculator/` — the repair estimate calculator (v5). Moved here from a Squarespace Code Block so it works on the Basic plan. `noindex` until besafetravels.com links to it.
  - Leads go to the calculator's Google Apps Script web app (lead-receiver v3.3+). The page holds **no secret**; the script checks a hidden bot-trap field, fill time, field rules and a rate limit.
  - Make/model suggestions (`MODELS`) are copied from the fix-or-trade tool's list. Update both together.
  - Pricing rules and multipliers: see `CLAUDE.md` in the private repo. Test NHTSA lookups on the live page (they're blocked from Claude's environment).

**This repo is public: never commit secrets.** A push to `main` goes live within about 2 minutes.
Project notes, status and decisions live in the private `CassSuczeck/calculator` repo (`PROJECT-STATUS.md`, `CLAUDE.md`, `BRAND.md`).
