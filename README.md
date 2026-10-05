# Safe Travels tools

Public home of Safe Travels Mobile Repair's customer tools, served by GitHub Pages at **tools.besafetravels.com**.

- `/` — placeholder (not indexed) until the tools launch.
- `/calculator/` — the repair estimate calculator (v5). Moved here from a Squarespace Code Block so it works on the Basic plan. Launched 2026-10-02: besafetravels.com/calculator links here, and search engines may index it.
  - Leads go to the calculator's Google Apps Script web app (lead-receiver v3.3+). The page holds **no secret**; the script checks a hidden bot-trap field, fill time, field rules and a rate limit.
  - Make/model suggestions (`MODELS`) are copied from the fix-or-trade tool's list. Update both together.
  - Pricing rules and multipliers: see `CLAUDE.md` in the private repo. Test NHTSA lookups on the live page (they're blocked from Claude's environment).

- `/fix-or-trade/` — "Fix it, or trade it in?" decision tool. Moved here from the `CassSuczeck/fix-or-trade` GitHub Pages site on 2026-10-05; **this copy is now the one to edit.** Still `noindex` until it's linked (F1). Leads go to its own Apps Script (code in `CassSuczeck/fix-or-trade/apps-script/`). Vehicles Safe Travels doesn't service (EVs, exotic makes, Maserati MC20/MCPura, model years before 1996) get a referral instead of a booking button, matching the calculator. Make/model lists are shared with the calculator; update both together.

**This repo is public: never commit secrets.** A push to `main` goes live within about 2 minutes.
Project notes, status and decisions live in the private `CassSuczeck/calculator` repo (`PROJECT-STATUS.md`, `CLAUDE.md`, `BRAND.md`).
