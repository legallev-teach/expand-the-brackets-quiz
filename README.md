# 🌈 Expand the Brackets — Quiz

An interactive, single-file HTML quiz for Form 1 Mathematics covering the distributive law: `a(bx + k)`.

## Features
- **Animated arc diagrams** showing the multiplier travelling to each term
- **Revise mode** — 3-step guided walkthrough, not assessed
- **Test mode** — 10 questions, teacher-code gated, score submitted to Google Forms
- **Toggle mode** (Q6–10) — students choose ± signs for negative products
- Instant green/orange feedback per term
- Hint system with mark cap in Test mode
- Mobile and tablet responsive

## Deployment
1. Download `distributive-law-quiz.html`
2. Host on Google Sites, GitHub Pages, or share the raw file directly
3. Students open in any browser — no install, no dependencies

## Teacher Setup
- Test code: set `TEST_CODE` near the top of the script
- Teacher panel: click the small grey dot at the bottom of the page, PIN required
- Google Forms: entry IDs and form URL are already configured in `submitToGoogleForm()`
- Close date: set `TEST_CLOSE_DATE` to auto-lock the test after your window

## Question Data
Edit `QsRevise` and `QsTest` arrays to customise questions. Each question: `{ a, bx, bk, xa, ka }`.

## Part of a Series
| Quiz | Topic |
|------|-------|
| Like Terms | Collecting and simplifying |
| **Expand the Brackets** | Distributive law ← this one |
| Expand and Simplify | Combined expansion + collection |
