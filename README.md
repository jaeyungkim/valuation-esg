# Valuation — Discount Rates, the SDF & ESG — student site (Summer ESG Module)

Public GitHub Pages site of **pre-class** materials for the Summer ESG valuation session.
Served at **https://jaeyungkim.github.io/valuation-esg/** (set in Settings → Pages).

## What's here (pre-class / no-answers only)
- `index.html` — landing page.
- `valuation_theory_preclass.html` + `Valuation_Theory_2026_preclass.pdf` — the theory lecture: the
  discount-rate framework and the predictions to commit to (the empirical answers are hidden).
- `spacex_valuation_preclass.html` + `SpaceX_Valuation_2026_preclass.pdf` — the SpaceX valuation case:
  the setup, the data, and the questions (the valuation and the verdicts are hidden).
- `reading_list_valuation.html` — the core + further reading list.

The two pre-class HTML files are **hardened**: the gated answers are physically removed from the page
*source* (not merely hidden by JavaScript), so even view-source reveals nothing. They are produced from
the private master by `make_public.py`.

## Adding the full materials after class
Copy these from the private master repo (`ESG-Valuation-Lecture`) into this folder and add a link/card to
`index.html`:
- **lecture** — slides `valuation_theory_full.html` + `Valuation_Theory_2026.pdf`; written reading `valuation_theory_textbook.html`
- **case** — slides `spacex_valuation_full.html` + `SpaceX_Valuation_2026.pdf`; written reading `spacex_valuation_textbook.html`

The written-reading editions (textbook / Korean-DC / bilingual) carry the full analysis and verdicts, so
they stay in the private repo until each session has run.

## Never publish here
The MCQ quiz/practice files + answer key, the Excel valuation model, the *during*-class HTML (answers
behind a click-to-reveal, so they sit in the page source), and the raw `.tex` / source files. These live
only in the private master repo.
