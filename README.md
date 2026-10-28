# Sell & Buy Calculator

**Archived (Oct 28, 2026).** Old links are forwarded by charlescarper.com itself. **Moved (Oct 22, 2026).** The calculator now lives on the main site at [charlescarper.com/plan/sell-and-buy/](https://charlescarper.com/plan/sell-and-buy/) (source: `js/sell-buy-calc.js` in ccarper03.github.io). `index.html` and `classic.html` here only forward old links there. The notes below describe the original page.

A one-page calculator for buyers who have a home to sell. Four sliders (what the home might sell for, what's owed, the monthly payment, and when they want to move in) drive three side-by-side ways to do it:

1. Sell first, then buy
2. Buy first, then sell, with a switch for a buy-before-you-sell program
3. Buy with a home-sale contingency

Each way shows moves, months paying for two homes, extra cost, cash left after the sale, and one thing to watch. "Text me about way N" buttons fill in a text with the visitor's numbers. Nothing a visitor enters is saved or sent anywhere unless they send that text themselves.

The page uses the main site's `/site.css` and `/site.js`, so it shares the header, footer, Ask Charles button and GA4 click tracking.

## Assumptions

- Selling costs 6%, months to sell 2 (both adjustable on the page).
- Buy first: half a month to prep after moving, then the months to sell, counting the full payment each month.
- Buy-before-you-sell program: one national program's published terms (October 2026), 2.25% of list price plus about $1,850, 0% interest for 6 months, total debt up to 75% of the home's value. The page doesn't name the program.

Planning estimates only, not financial or lending advice.

## classic.html

The original sales-table Home-to-Sell Planner (ranked options, month-by-month timeline, buyer text and CRM follow-ups), kept unlisted at `/home-to-sell-planner/classic.html`. Knock terms updated October 18, 2026.

Built by Charles Carper.
